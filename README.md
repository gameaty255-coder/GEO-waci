
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>game-keyword-miner Skill 文档</title>
</head>
<body>

<div class="header-box">
    <h1>🎮 game-keyword-miner</h1>
    <p class="meta">
        <strong>游戏潜在用户关键词挖掘工具升级版v2.0</strong><br>
        支持12+挖词维度和搜索引擎验证的专业游戏关键词挖掘工具
    </p>
    <p class="meta">
        <span class="tag">v2.0.0</span>
        <span class="tag">SEO</span>
        <span class="tag">关键词挖掘</span>
    </p>
</div>

<h2>📋 触发条件</h2>
<p>当用户提及以下场景时激活：</p>
<ul>
    <li>"挖掘游戏关键词" / "游戏SEO关键词" / "帮我挖词"</li>
    <li>"生成游戏标签" / "验证搜索热度" / "游戏营销关键词"</li>
    <li>"需要游戏相关的搜索词" / "关键词拓展" / "游戏推广词"</li>
</ul>

<h2>⚡ 核心能力</h2>

<h3>1. 12+ 挖词维度</h3>
<table>
    <tr>
        <th>分类</th>
        <th>数量</th>
        <th>说明</th>
        <th>示例</th>
    </tr>
    <tr>
        <td>🏆 <strong>排行热门</strong></td>
        <td>20</td>
        <td>用户找热门排行时搜索</td>
        <td>2026最多人玩的游戏、最火的开放世界游戏排行</td>
    </tr>
    <tr>
        <td>✅ <strong>适合人群</strong></td>
        <td>25</td>
        <td>用户有明确人群需求时搜索</td>
        <td>适合女生的游戏、适合学生党的游戏、适合搬砖的游戏</td>
    </tr>
    <tr>
        <td>❓ <strong>什么游戏</strong></td>
        <td>25</td>
        <td>用户不确定玩什么时搜索</td>
        <td>什么游戏好玩、什么游戏不氪金、什么游戏能赚钱</td>
    </tr>
    <tr>
        <td>📝 <strong>描述属性</strong></td>
        <td>30</td>
        <td>用户有特定属性需求时搜索</td>
        <td>不肝不氪的MMO、可以捏脸的游戏、剧情好的RPG</td>
    </tr>
    <tr>
        <td>💰 <strong>赚钱搬砖</strong></td>
        <td>25</td>
        <td>用户想游戏赚钱时搜索</td>
        <td>一个月赚5000的游戏、能搬砖的武侠游戏</td>
    </tr>
    <tr>
        <td>📊 <strong>推荐搜索</strong></td>
        <td>25</td>
        <td>用户求推荐时搜索</td>
        <td>游戏推荐、求推荐手游、必玩神作</td>
    </tr>
    <tr>
        <td>🎮 <strong>平台设备</strong></td>
        <td>25</td>
        <td>用户有设备限制时搜索</td>
        <td>手机能玩的游戏、低配置游戏、千元机能玩的游戏</td>
    </tr>
    <tr>
        <td>📅 <strong>时间档期</strong></td>
        <td>24</td>
        <td>用户关注新游时搜索</td>
        <td>2026年新游戏、即将上线的游戏、新公测的手游</td>
    </tr>
    <tr>
        <td>⚔️ <strong>对比替代</strong></td>
        <td>18</td>
        <td>用户找竞品时搜索</td>
        <td>类似原神的游戏、逆水寒平替、除了原神还有</td>
    </tr>
    <tr>
        <td>🎯 <strong>难度门槛</strong></td>
        <td>14</td>
        <td>用户担心难度时搜索</td>
        <td>新手友好的游戏、适合手残党的游戏</td>
    </tr>
    <tr>
        <td>⏱️ <strong>耐玩度</strong></td>
        <td>14</td>
        <td>用户担心内容少时搜索</td>
        <td>耐玩的游戏、能长期玩的游戏、不会腻的游戏</td>
    </tr>
    <tr>
        <td>💎 <strong>付费肝度</strong></td>
        <td>17</td>
        <td>用户关心氪金时搜索</td>
        <td>不肝不氪的游戏、零氪能玩的游戏、良心游戏</td>
    </tr>
    <tr>
        <td>🏷️ <strong>游戏名相关</strong></td>
        <td>23</td>
        <td>用户搜索特定游戏时</td>
        <td>燕云十六声怎么样、燕云十六声攻略、燕云十六声氪金吗</td>
    </tr>
</table>

<h3>2. 搜索引擎验证</h3>
<div class="feature-box">
    <p>自动调用 <strong>百度/谷歌</strong> 搜索建议 API 验证关键词：</p>
    <table>
        <tr>
            <th>状态</th>
            <th>标记</th>
            <th>说明</th>
        </tr>
        <tr>
            <td><span class="status-yes">✅ 已验证</span></td>
            <td>[✓]</td>
            <td>搜索引擎有相关下拉建议</td>
        </tr>
        <tr>
            <td><span class="status-no">❌ 未验证</span></td>
            <td>[○]</td>
            <td>搜索量较低或无明显相关建议</td>
        </tr>
    </table>
</div>

<h3>3. 置信度分级</h3>
<table>
    <tr>
        <th>等级</th>
        <th>标记</th>
        <th>说明</th>
    </tr>
    <tr>
        <td><span class="badge badge-high">🔥 High</span></td>
        <td>高置信度</td>
        <td>搜索引擎有强相关建议</td>
    </tr>
    <tr>
        <td><span class="badge badge-medium">⭐ Medium</span></td>
        <td>中置信度</td>
        <td>有间接相关建议</td>
    </tr>
    <tr>
        <td><span class="badge badge-low">📌 Low</span></td>
        <td>低置信度</td>
        <td>建议较少或网络问题</td>
    </tr>
</table>

<h2>🔧 使用方法</h2>

<h3>基础用法</h3>
<pre><code>python3 keyword_miner.py "游戏名" "游戏类型" "竞品1,竞品2" "模式" [--verify/--no-verify]</code></pre>

<h3>参数说明</h3>
<table>
    <tr>
        <th>参数</th>
        <th>必填</th>
        <th>说明</th>
    </tr>
    <tr>
        <td>游戏名</td>
        <td><span class="status-yes">✅</span></td>
        <td>目标游戏名称，如"燕云十六声"</td>
    </tr>
    <tr>
        <td>游戏类型</td>
        <td><span class="status-yes">✅</span></td>
        <td>游戏分类，如"开放世界游戏"、"回合制网游"</td>
    </tr>
    <tr>
        <td>竞品</td>
        <td><span class="status-no">❌</span></td>
        <td>竞品游戏，逗号分隔，如"原神,逆水寒"</td>
    </tr>
    <tr>
        <td>模式</td>
        <td><span class="status-no">❌</span></td>
        <td>生成模式：all/genre_only，默认all</td>
    </tr>
    <tr>
        <td>--verify</td>
        <td><span class="status-no">❌</span></td>
        <td>开启搜索引擎验证（推荐）</td>
    </tr>
    <tr>
        <td>--no-verify</td>
        <td><span class="status-no">❌</span></td>
        <td>关闭验证，快速生成</td>
    </tr>
</table>

<h3>示例</h3>
<pre><code># 基础挖掘（开启验证）
python3 keyword_miner.py "燕云十六声" "开放世界游戏"

# 指定竞品 + 验证
python3 keyword_miner.py "燕云十六声" "武侠游戏" "原神,逆水寒" all --verify

# 仅生成类型词 + 验证
python3 keyword_miner.py "燕云十六声" "开放世界游戏" "" "genre_only" --verify

# 关闭验证（快速生成）
python3 keyword_miner.py "燕云十六声" "开放世界游戏" "" "all" --no-verify</code></pre>

<h2>📊 输出结果</h2>

<h3>控制台输出示例</h3>
<pre>
🎮 游戏名称: 燕云十六声
📂 游戏类型: 开放世界游戏
🔍 搜索验证: 开启

================================================================================
📊 「燕云十六声」关键词挖掘结果
   游戏类型: 开放世界游戏
================================================================================

【排行热门】(20个, 已验证:15, 高置信:12)
  [✓] 🔥 2026最多人玩的游戏
  [✓] 🔥 最火的开放世界游戏排行
  [✓] 🔥 2026年最火的游戏
  ...

【适合人群】(26个, 已验证:26, 高置信:16)
  [✓] 🔥 适合新手的开放世界游戏
  [✓] 🔥 适合武侠迷的开放世界游戏
  ...

================================================================================
✅ 共生成 294 个关键词
   已验证: 294 | 高置信度: 198
================================================================================
💾 CSV: 燕云十六声_关键词验证.csv
</pre>

<h3>CSV 输出格式</h3>
<table>
    <tr>
        <th>字段</th>
        <th>说明</th>
    </tr>
    <tr>
        <td><strong>分类</strong></td>
        <td>关键词所属类别（如：排行热门、适合人群）</td>
    </tr>
    <tr>
        <td><strong>关键词</strong></td>
        <td>完整关键词短语</td>
    </tr>
    <tr>
        <td><strong>预估热度</strong></td>
        <td>高/中/低</td>
    </tr>
    <tr>
        <td><strong>验证状态</strong></td>
        <td>已验证/未验证</td>
    </tr>
    <tr>
        <td><strong>置信度</strong></td>
        <td>high/medium/low</td>
    </tr>
    <tr>
        <td><strong>相似词</strong></td>
        <td>搜索引擎返回的相关建议（JSON格式）</td>
    </tr>
</table>

<h2>🎯 用户搜索场景映射</h2>

<div class="feature-box">
    <h4>场景 1：用户想找排行</h4>
    <p><em>"2026年什么游戏最火？"</em></p>
    <p><strong>触发关键词</strong>：排行热门类</p>
    <ul>
        <li>2026最多人玩的游戏</li>
        <li>最火的开放世界游戏排行</li>
        <li>下载量最高的武侠游戏</li>
    </ul>
</div>

<div class="feature-box">
    <h4>场景 2：用户有明确需求</h4>
    <p><em>"适合女生玩的游戏" / "适合上班摸鱼的游戏"</em></p>
    <p><strong>触发关键词</strong>：适合人群类</p>
    <ul>
        <li>适合女生的武侠游戏</li>
        <li>适合打工人的开放世界游戏</li>
        <li>适合休闲的MMO</li>
    </ul>
</div>

<div class="feature-box">
    <h4>场景 3：用户想赚钱</h4>
    <p><em>"什么游戏能搬砖赚钱？"</em></p>
    <p><strong>触发关键词</strong>：赚钱搬砖类</p>
    <ul>
        <li>一个月赚5000的游戏</li>
        <li>能搬砖的武侠游戏</li>
        <li>可以自由交易的开放世界游戏</li>
    </ul>
</div>

<div class="feature-box">
    <h4>场景 4：用户有特定要求</h4>
    <p><em>"不想太肝太氪的游戏" / "剧情好的游戏"</em></p>
    <p><strong>触发关键词</strong>：描述属性类</p>
    <ul>
        <li>不肝不氪的武侠游戏</li>
        <li>剧情丰富的开放世界游戏</li>
        <li>可以捏脸的MMO</li>
    </ul>
</div>

<div class="feature-box">
    <h4>场景 5：用户在对比</h4>
    <p><em>"原神玩腻了，有什么类似的？"</em></p>
    <p><strong>触发关键词</strong>：对比替代类</p>
    <ul>
        <li>类似原神的游戏</li>
        <li>原神平替</li>
        <li>除了原神还有</li>
    </ul>
</div>

<h2>✨ 最佳实践</h2>

<h3>1. 挖掘前准备</h3>
<ul>
    <li>明确游戏的核心卖点（剧情？画质？玩法？）</li>
    <li>确定目标用户群体（学生？上班族？硬核玩家？）</li>
    <li>了解竞品情况（直接竞品 + 间接竞品）</li>
</ul>

<h3>2. 挖掘策略</h3>
<div class="tip-box">
    <ul>
        <li><strong>新品上线</strong>：重点挖掘"时间档期" + "排行热门"</li>
        <li><strong>长线运营</strong>：重点挖掘"耐玩度" + "赚钱搬砖"</li>
        <li><strong>用户获取</strong>：重点挖掘"适合人群" + "什么游戏"</li>
        <li><strong>口碑维护</strong>：重点挖掘"描述属性" + "游戏名相关"</li>
    </ul>
</div>

<h3>3. 结果应用</h3>
<ul>
    <li><strong>高置信度词</strong>：优先用于SEO标题和Meta</li>
    <li><strong>中置信度词</strong>：用于内容创作和标签</li>
    <li><strong>未验证词</strong>：可作为潜在需求监控</li>
</ul>

<h2>❓ 常见问题</h2>

<div class="highlight-box">
    <h4>Q1: 验证失败怎么办？</h4>
    <p>验证失败时会自动切换到 <strong>模拟验证模式</strong>（基于关键词特征评估），仍可提供参考价值。</p>
</div>

<div class="highlight-box">
    <h4>Q2: 为什么有些词验证为Low？</h4>
    <p>可能原因：</p>
    <ul>
        <li>搜索量较低，无明显下拉建议</li>
        <li>网络请求超时</li>
        <li>该词属于长尾词，搜索频率不高</li>
    </ul>
</div>

<div class="highlight-box">
    <h4>Q3: 批量处理时如何提速？</h4>
    <p>建议关闭验证（--no-verify）快速生成所有词，最后对精选词单独验证。</p>
</div>

<div class="highlight-box">
    <h4>Q4: 结果会随时间变化吗？</h4>
    <p>会。搜索趋势会随时间变化，建议：</p>
    <ul>
        <li>新品上线前：每周验证一次</li>
        <li>稳定运营期：每月验证一次</li>
        <li>大版本更新后：重新验证</li>
    </ul>
</div>


<h2>📁 输出文件示例</h2>
<pre><code>分类,关键词,预估热度,验证状态,置信度,相似词
排行热门,2026最多人玩的游戏,高,已验证,high,"2026最多人玩的游戏游戏, 2026最多人玩的游戏推荐"
适合人群,适合女生的开放世界游戏,高,已验证,high,"适合女生的开放世界游戏推荐, 适合女生的武侠游戏"
赚钱搬砖,一个月赚5000的游戏,高,已验证,high,"一个月赚5000的游戏推荐, 能赚钱的游戏"
描述属性,剧情丰富的开放世界游戏,高,已验证,high,"剧情丰富的武侠游戏, 剧情好的开放世界游戏"</code></pre>

<hr>

<div class="footer">
    <p><strong>game-keyword-miner</strong> v2.0.0</p>
    <p>更新时间：2026-03-12</p>
</div>

</body>
</html>
