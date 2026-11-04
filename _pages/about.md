---
permalink: /
title: "Yanjie Li | AI Security Researcher / 人工智能安全研究者"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
.home-duo{--ink:#172b4d;--muted:#52647d;--blue:#2763a5;--cyan:#83d7df;--coral:#fa846f;--line:#dce5ee;color:var(--ink);max-width:100%}
.home-duo *{box-sizing:border-box}
.home-duo [data-lang]{display:none!important}
.home-duo[data-current-lang=en] [data-lang=en],.home-duo[data-current-lang=zh] [data-lang=zh]{display:block!important}
.home-duo .topline{display:flex;align-items:center;justify-content:space-between;gap:1rem;margin:0 0 1rem;color:var(--muted);font-size:.76rem;letter-spacing:.08em;text-transform:uppercase}
.home-duo .switch{display:inline-flex;gap:.2rem;padding:.22rem;border:1px solid var(--line);border-radius:99px;background:#fff;letter-spacing:0;text-transform:none}
.home-duo .switch button{border:0;border-radius:99px;padding:.38rem .7rem;color:var(--muted);background:transparent;cursor:pointer;font:inherit;font-weight:750}
.home-duo .switch button[aria-pressed=true]{color:#fff;background:var(--ink)}
.home-duo .switch button:focus-visible,.home-duo a:focus-visible{outline:3px solid var(--coral);outline-offset:3px}
.home-duo .hero{display:grid;grid-template-columns:1.1fr .9fr;align-items:center;gap:1.5rem;overflow:hidden;margin-bottom:2rem;padding:clamp(1.3rem,4vw,2.6rem);border:1px solid #d9e6ef;border-radius:22px;background:linear-gradient(135deg,#f8fbff,#eff8fa 58%,#fff5f1);box-shadow:0 14px 38px #172b4d12}
.home-duo .eyebrow{margin:0 0 .6rem;color:var(--blue);font-size:.73rem;font-weight:850;letter-spacing:.14em;text-transform:uppercase}
.home-duo h1{margin:0;color:var(--ink);font-size:clamp(2.2rem,5vw,3.5rem);letter-spacing:-.045em;line-height:1.05}
.home-duo .role{margin:.65rem 0;color:var(--blue);font-size:1.1rem;font-weight:800}
.home-duo .intro{max-width:40rem;color:#344962;font-size:1rem;line-height:1.75}
.home-duo .quip{color:#60718a;font-size:.9rem;font-style:italic}
.home-duo .actions,.home-duo .contact-links{display:flex;flex-wrap:wrap;gap:.6rem;margin-top:1rem}
.home-duo .actions a{padding:.6rem .88rem;border:1px solid #cad8e7;border-radius:99px;color:var(--ink);background:#ffffffc9;font-size:.84rem;font-weight:750;text-decoration:none}
.home-duo .actions a:first-child{border-color:var(--blue);color:white;background:var(--blue)}
.home-duo .diagram{width:100%;height:auto}
.home-duo .diagram text{font:700 11px -apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;fill:#52647d}
.home-duo .diagram text[data-lang]{display:none}
.home-duo[data-current-lang=en] .diagram text[data-lang=en],.home-duo[data-current-lang=zh] .diagram text[data-lang=zh]{display:block}
.home-duo .section{margin:2rem 0}
.home-duo .section-head{display:flex;align-items:end;justify-content:space-between;gap:1rem;margin-bottom:.9rem;padding-bottom:.6rem;border-bottom:1px solid var(--line)}
.home-duo .section-head h2{margin:0;color:var(--ink);font-size:1.4rem}
.home-duo .kicker{margin:0;color:#8190a3;font-size:.7rem;font-weight:850;letter-spacing:.12em;text-transform:uppercase}
.home-duo .grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:.85rem}
.home-duo .card{height:100%;padding:1rem;border:1px solid var(--line);border-radius:14px;background:#fff;box-shadow:0 5px 17px #172b4d09}
.home-duo .card .num{color:var(--blue);font-size:.75rem;font-weight:900}
.home-duo .card h3{margin:.35rem 0;color:var(--ink);font-size:1rem}
.home-duo .card p,.home-duo .project p,.home-duo .paper p{margin:.35rem 0 0;color:var(--muted);font-size:.87rem;line-height:1.65}
.home-duo .projects{display:grid;gap:.7rem}
.home-duo .project{display:grid;grid-template-columns:minmax(8rem,.25fr) 1fr;gap:.9rem;padding:.9rem 1rem;border-left:3px solid var(--cyan);border-radius:0 12px 12px 0;background:#f6f8fb}
.home-duo .project:nth-child(2){border-color:var(--coral)}.home-duo .project:nth-child(3){border-color:var(--blue)}
.home-duo .project strong{color:var(--ink)}.home-duo .meta{display:block;margin-top:.2rem;color:#75859a;font-size:.75rem}
.home-duo .papers{display:grid;gap:.65rem;padding:0;list-style:none;counter-reset:p}
.home-duo .paper{position:relative;padding:.75rem .85rem .75rem 2.5rem;border:1px solid var(--line);border-radius:11px;background:#fff;counter-increment:p}
.home-duo .paper:before{content:counter(p,decimal-leading-zero);position:absolute;left:.75rem;top:.8rem;color:var(--blue);font-size:.73rem;font-weight:900}
.home-duo .paper strong{color:var(--ink);font-size:.88rem}.home-duo a{color:var(--blue)}
.home-duo .facts{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:.8rem}
.home-duo .fact{padding:.95rem;border-radius:13px;background:#f4f7fa}
.home-duo .fact h3{margin:0 0 .4rem;color:var(--ink);font-size:.96rem}
.home-duo .fact ul{margin:0;padding-left:1.1rem;color:var(--muted);font-size:.85rem;line-height:1.7}
.home-duo .contact{padding:1.15rem;border:1px solid #c9dce9;border-radius:15px;background:linear-gradient(120deg,#f3f9fc,#fff6f2)}
.home-duo .contact p{margin:.3rem 0;color:var(--muted);font-size:.9rem}
.home-duo .contact-links{gap:.5rem 1rem;font-size:.84rem}
.home-duo .foot{color:#8190a3;font-size:.75rem;text-align:center}
@media(max-width:760px){.home-duo .hero{grid-template-columns:1fr}.home-duo .diagram{max-width:30rem;margin:auto}.home-duo .grid{grid-template-columns:1fr}.home-duo .project{grid-template-columns:1fr;gap:.2rem}}
@media(max-width:520px){.home-duo .topline{align-items:start;flex-direction:column}.home-duo .facts{grid-template-columns:1fr}}
</style>

<div class="home-duo" id="homeDuo" data-current-lang="en">
  <div class="topline">
    <div data-lang="en">Research from Hong Kong · Secure AI, useful AI</div>
    <div data-lang="zh">来自香港的研究手记 · 让 AI 既有用，也靠谱</div>
    <div class="switch" role="group" aria-label="Language / 语言">
      <button type="button" data-language="en" aria-pressed="true" aria-label="Switch to English">EN</button>
      <button type="button" data-language="zh" aria-pressed="false" aria-label="切换到中文">中文</button>
    </div>
  </div>

  <header class="hero">
    <div>
      <p class="eyebrow" data-lang="en">AI security · research · the real world</p><p class="eyebrow" data-lang="zh">人工智能安全 · 学术研究 · 真实世界</p>
      <h1>Yanjie Li</h1>
      <div class="role" data-lang="en">AI Security Researcher</div><div class="role" data-lang="zh">人工智能安全研究者</div>
      <p class="intro" data-lang="en">I am a Postdoctoral Fellow at The Hong Kong Polytechnic University. I study LLM agent security, multimodal robustness, and adversarial attacks that leave the screen and meet the physical world.</p>
      <p class="intro" data-lang="zh">我现任香港理工大学博士后，研究大语言模型智能体安全、多模态鲁棒性，以及从屏幕走进现实世界的对抗攻击。</p>
      <p class="quip" data-lang="en">I want AI to be helpful—just not so helpful that it hands the keys to a suspicious tool call.</p>
      <p class="quip" data-lang="zh">我希望 AI 乐于助人——但最好别热心到把钥匙交给一个可疑的工具调用。</p>
      <div class="actions">
        <a href="/publications/"><span data-lang="en">Browse papers ↗</span><span data-lang="zh">查看论文 ↗</span></a>
        <a href="/cv/"><span data-lang="en">Full CV ↗</span><span data-lang="zh">完整简历 ↗</span></a>
      </div>
    </div>
    <svg class="diagram" viewBox="0 0 520 300" role="img" aria-label="Agent tool-call security illustration">
      <defs><linearGradient id="panelDuo" x1="0" x2="1" y1="0" y2="1"><stop stop-color="#fff"/><stop offset="1" stop-color="#eaf5fa"/></linearGradient><filter id="shadowDuo" x="-20%" y="-20%" width="140%" height="150%"><feDropShadow dx="0" dy="7" stdDeviation="8" flood-color="#52647d" flood-opacity=".13"/></filter></defs>
      <path d="M85 146H224M294 146H420" fill="none" stroke="#91a8bc" stroke-width="3" stroke-dasharray="6 7"/><path d="m408 137 13 9-13 9" fill="none" stroke="#91a8bc" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
      <g filter="url(#shadowDuo)"><rect x="18" y="92" width="110" height="108" rx="18" fill="url(#panelDuo)" stroke="#d6e2ec"/><rect x="154" y="92" width="110" height="108" rx="18" fill="url(#panelDuo)" stroke="#d6e2ec"/><rect x="290" y="92" width="110" height="108" rx="18" fill="#eef8f8" stroke="#b8e2e1"/><rect x="426" y="92" width="76" height="108" rx="18" fill="#fff3ef" stroke="#f3d3ca"/></g>
      <circle cx="73" cy="128" r="15" fill="#83d7df"/><path d="M49 173c2-22 46-22 48 0" fill="none" stroke="#2763a5" stroke-width="7" stroke-linecap="round"/>
      <rect x="192" y="113" width="34" height="29" rx="8" fill="#2763a5"/><circle cx="201" cy="127" r="2.5" fill="#fff"/><circle cx="217" cy="127" r="2.5" fill="#fff"/><path d="M200 151q9 8 18 0" fill="none" stroke="#fa846f" stroke-width="3" stroke-linecap="round"/>
      <path d="m345 112 25 9v20c0 19-12 31-25 38-13-7-25-19-25-38v-20z" fill="#83d7df"/><path d="m335 143 7 7 14-16" fill="none" stroke="#173b61" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
      <rect x="448" y="120" width="33" height="34" rx="7" fill="#fa846f"/><path d="M455 128h19m-19 8h19m-19 8h14" stroke="#fff" stroke-width="2.4" stroke-linecap="round"/>
      <path d="M265 75c19-19 39-17 49 0" fill="none" stroke="#fa846f" stroke-width="2.5" stroke-dasharray="4 4"/><circle cx="289" cy="66" r="14" fill="#fff3ef" stroke="#f3d3ca"/><path d="m283 60 12 12m0-12-12 12" stroke="#fa846f" stroke-width="2.8" stroke-linecap="round"/>
      <text x="73" y="226" text-anchor="middle" data-lang="en">USER</text><text x="73" y="226" text-anchor="middle" data-lang="zh">用户</text>
      <text x="209" y="226" text-anchor="middle" data-lang="en">AGENT</text><text x="209" y="226" text-anchor="middle" data-lang="zh">智能体</text>
      <text x="345" y="226" text-anchor="middle" data-lang="en">POLICY CHECK</text><text x="345" y="226" text-anchor="middle" data-lang="zh">策略校验</text>
      <text x="464" y="226" text-anchor="middle" data-lang="en">TOOL</text><text x="464" y="226" text-anchor="middle" data-lang="zh">工具</text>
      <text x="289" y="43" text-anchor="middle" fill="#c45f4d" font-size="10" font-weight="700"><tspan data-lang="en">“ignore the user”</tspan><tspan data-lang="zh">“忽略用户”</tspan></text>
    </svg>
  </header>

  <section class="section">
    <div class="section-head"><h2 data-lang="en">Research, in plain terms</h2><h2 data-lang="zh">研究方向，一句话讲清楚</h2><p class="kicker" data-lang="en">What I work on</p><p class="kicker" data-lang="zh">关注的问题</p></div>
    <p data-lang="en">I ask a deceptively simple question: what <em>can</em> an AI system do, and what <em>should</em> it do? The answer usually takes a careful threat model, a few red-team surprises, and more experiments.</p>
    <p data-lang="zh">我常问一个看似简单的问题：AI 系统“能做什么”，和“应该做什么”，是不是一回事？答案通常需要严谨的威胁模型、几次红队意外，以及更多实验。</p>
    <div class="grid">
      <article class="card"><div class="num">01</div><h3 data-lang="en">Agent security</h3><h3 data-lang="zh">智能体安全</h3><p data-lang="en">Runtime safeguards, tool-use authorization, and automated red-teaming for agents that can take actions.</p><p data-lang="zh">为能够执行操作的智能体设计运行时防护、工具调用授权机制与自动化红队评测。</p></article>
      <article class="card"><div class="num">02</div><h3 data-lang="en">Multimodal robustness</h3><h3 data-lang="zh">多模态鲁棒性</h3><p data-lang="en">Testing how visual and textual content may steer models toward unintended or unauthorized actions.</p><p data-lang="zh">研究图像与文本内容如何诱导模型做出非预期或未经授权的行为。</p></article>
      <article class="card"><div class="num">03</div><h3 data-lang="en">Physical-world attacks</h3><h3 data-lang="zh">物理世界对抗攻击</h3><p data-lang="en">Adversarial methods for person detection and 3D face recognition beyond the lab screen.</p><p data-lang="zh">探索针对行人检测与三维人脸识别的对抗攻击，让实验不止停留在屏幕里。</p></article>
    </div>
  </section>

  <section class="section">
    <div class="section-head"><h2 data-lang="en">A few things I have built or studied</h2><h2 data-lang="zh">做过的一些研究</h2><p class="kicker" data-lang="en">Selected work</p><p class="kicker" data-lang="zh">研究片段</p></div>
    <div class="projects">
      <article class="project"><div><strong>GuardAgent</strong><span class="meta">ICML 2025 · Agent safeguards</span></div><div><p data-lang="en">Led dynamic access-control verification that checks an agent’s tool calls against user intent. A helpful agent should still know when to ask, “Did you actually mean that?”</p><p data-lang="zh">主导动态访问控制验证，检查智能体的工具调用是否符合用户意图。再热心的智能体，也该知道什么时候先问一句：“你确定是这个意思吗？”</p></div></article>
      <article class="project"><div><strong>SecureAgent</strong><span class="meta" data-lang="en">Multimodal red-teaming</span><span class="meta" data-lang="zh">多模态红队评测</span></div><div><p data-lang="en">Evaluation scenarios for indirect and adaptive prompt injection carried in external visual and textual content.</p><p data-lang="zh">设计评测场景，研究藏在外部图像和文本中的间接、自适应提示注入。</p></div></article>
      <article class="project"><div><strong>UV-Attack · SLAttack</strong><span class="meta" data-lang="en">Physical and digital robustness</span><span class="meta" data-lang="zh">物理与数字世界鲁棒性</span></div><div><p data-lang="en">Work on dynamic-NeRF UV mapping, structured-light attacks, LVLM projector vulnerabilities, and cross-model transferability.</p><p data-lang="zh">研究动态 NeRF UV 映射、结构光攻击、视觉语言模型投影器脆弱性与跨模型迁移攻击。</p></div></article>
      <article class="project"><div><strong>AgentFence</strong><span class="meta" data-lang="en">Proposed research agenda</span><span class="meta" data-lang="zh">提出的研究议程</span></div><div><p data-lang="en">Verifiable runtime authorization through policy compilation, authority-expansion detection, least-authority repair, and adaptive evaluation.</p><p data-lang="zh">围绕可验证的运行时授权展开：策略编译、权限扩张检测、最小权限修复与自适应安全评测。</p></div></article>
    </div>
  </section>

  <section class="section">
    <div class="section-head"><h2 data-lang="en">Selected publications</h2><h2 data-lang="zh">代表性论文</h2><p class="kicker" data-lang="en">A small sample</p><p class="kicker" data-lang="zh">部分成果</p></div>
    <ol class="papers">
      <li class="paper"><strong>StyleGuard: Preventing Text-to-Image-Model-based Style Mimicry Attacks by Style Perturbations</strong><p data-lang="en">NeurIPS 2025 · Yanjie Li, Wenxuan Zhang, Xinqi Lyu, Yihao Liu, and Bin Xiao.</p><p data-lang="zh">NeurIPS 2025 · 关于防止文本生成图像模型风格仿冒攻击的研究。作者：Yanjie Li、Wenxuan Zhang、Xinqi Lyu、Yihao Liu、Bin Xiao。</p></li>
      <li class="paper"><strong>UV-Attack: Physical-World Adversarial Attacks for Person Detection via Dynamic-NeRF-based UV Mapping</strong><p data-lang="en">ICLR 2025 · Yanjie Li, Kaisheng Liang, and Bin Xiao. <a href="https://github.com/PolyLiYJ/UV-Attack">Project code ↗</a></p><p data-lang="zh">ICLR 2025 · 基于动态 NeRF UV 映射的行人检测物理世界对抗攻击。作者：Yanjie Li、Kaisheng Liang、Bin Xiao。<a href="https://github.com/PolyLiYJ/UV-Attack">项目代码 ↗</a></p></li>
      <li class="paper"><strong>A Survey of Robustness and Safety of 2D and 3D Deep Learning Models Against Adversarial Attacks</strong><p data-lang="en">ACM Computing Surveys 56(9), Article 230, 2024 · Yanjie Li et al.</p><p data-lang="zh">ACM Computing Surveys 56(9), Article 230, 2024 · 二维与三维深度学习模型对抗鲁棒性和安全性综述 · Yanjie Li 等。</p></li>
      <li class="paper"><strong>Physical-World Optical Adversarial Attacks on 3D Face Recognition</strong><p data-lang="en">CVPR 2023, pp. 24699–24708 · Yanjie Li et al.</p><p data-lang="zh">CVPR 2023, pp. 24699–24708 · 面向三维人脸识别的物理世界光学对抗攻击 · Yanjie Li 等。</p></li>
      <li class="paper"><strong>GuardAgent: Safeguard LLM Agent by a Guard Agent via Knowledge-Enabled Reasoning</strong><p data-lang="en">ICML 2025 · Zhen Xiang, Linzhi Zheng, Yanjie Li, et al.</p><p data-lang="zh">ICML 2025 · 通过知识增强推理的守护智能体保护大语言模型智能体 · Zhen Xiang、Linzhi Zheng、Yanjie Li 等。</p></li>
      <li class="paper"><strong>IDS-Agent: An LLM Agent for Explainable Intrusion Detection in IoT Networks</strong><p data-lang="en">NeurIPS 2024 Workshop on Open-World Agents · Yanjie Li et al.</p><p data-lang="zh">NeurIPS 2024 Open-World Agents Workshop · 面向物联网可解释入侵检测的大语言模型智能体 · Yanjie Li 等。</p></li>
    </ol>
    <p data-lang="en">See the <a href="/publications/">full publications list</a> for more.</p><p data-lang="zh">更多论文与合作成果请见<a href="/publications/">完整论文列表</a>。</p>
  </section>

  <section class="section">
    <div class="section-head"><h2 data-lang="en">The short bio</h2><h2 data-lang="zh">经历速览</h2><p class="kicker" data-lang="en">A few dates</p><p class="kicker" data-lang="zh">几个时间点</p></div>
    <div class="facts">
      <div class="fact"><h3 data-lang="en">Now & before</h3><h3 data-lang="zh">工作经历</h3><ul data-lang="en"><li>Postdoctoral Fellow, PolyU · Sep 2026–present</li><li>Part-time Research Assistant, PolyU · Sep 2024–Aug 2025</li><li>Visiting Research Student, UIUC · Feb–Aug 2024</li></ul><ul data-lang="zh"><li>香港理工大学博士后 · 2026 年 9 月至今</li><li>香港理工大学兼职研究助理 · 2024 年 9 月–2025 年 8 月</li><li>伊利诺伊大学厄巴纳-香槟分校访问研究生 · 2024 年 2–8 月</li></ul></div>
      <div class="fact"><h3 data-lang="en">Degrees</h3><h3 data-lang="zh">教育经历</h3><ul data-lang="en"><li>PhD, Computer Science and Engineering, PolyU · 2021–2026</li><li>MSc, Control Science and Engineering, Zhejiang University · 2018–2021</li><li>BEng, Automation, Central South University · 2014–2018</li></ul><ul data-lang="zh"><li>香港理工大学 · 计算机科学与工程博士 · 2021–2026</li><li>浙江大学 · 控制科学与工程硕士 · 2018–2021</li><li>中南大学 · 自动化学士 · 2014–2018</li></ul></div>
      <div class="fact"><h3 data-lang="en">Teaching & service</h3><h3 data-lang="zh">教学与学术服务</h3><ul data-lang="en"><li>PolyU Teaching Assistant · Sep 2021–May 2024</li><li>Mentored five PhD and master's researchers</li><li>Reviewer for IEEE T-IFS, NeurIPS, ICLR, and CVPR</li></ul><ul data-lang="zh"><li>香港理工大学助教 · 2021 年 9 月–2024 年 5 月</li><li>指导 5 名博士生和硕士生</li><li>IEEE T-IFS、NeurIPS、ICLR、CVPR 审稿人</li></ul></div>
      <div class="fact"><h3 data-lang="en">A few honors</h3><h3 data-lang="zh">奖项片段</h3><ul data-lang="en"><li>Most Appreciated Teaching Assistant Award, Bronze · 2022</li><li>Best Paper Award, EI2 · 2019</li><li>Meritorious Winner, Mathematical Contest in Modeling · 2017</li></ul><ul data-lang="zh"><li>最受欢迎助教奖铜奖 · 2022</li><li>EI2 最佳论文奖 · 2019</li><li>美国大学生数学建模竞赛 Meritorious Winner · 2017</li></ul></div>
    </div>
    <p data-lang="en">I have also co-invented three Chinese invention patents and contributed to a GRF project on 3D point-cloud robustness. More details are in my <a href="/cv/">CV</a>.</p><p data-lang="zh">此外，我参与 3 项中国发明专利，并参与三维点云鲁棒性相关的 GRF 项目。更多经历见<a href="/cv/">完整简历</a>。</p>
  </section>

  <section class="section">
    <div class="section-head"><h2 data-lang="en">Say hello</h2><h2 data-lang="zh">欢迎联系</h2><p class="kicker" data-lang="en">Research chats welcome</p><p class="kicker" data-lang="zh">欢迎学术交流</p></div>
    <div class="contact">
      <p data-lang="en">Interested in agent security, robustness, or a careful debate about whether a model should trust that suspicious screenshot? I’m happy to talk.</p><p data-lang="zh">如果你也关注智能体安全、鲁棒性，或者想认真讨论模型该不该相信那张可疑截图，欢迎来聊。</p>
      <div class="contact-links"><a href="mailto:yanjie.li@connect.polyu.hk">Email</a><a href="https://scholar.google.com/citations?hl=en&amp;user=h3Chje4AAAAJ">Google Scholar</a><a href="https://orcid.org/0000-0001-8859-8331">ORCID</a><span data-lang="en">Phone: +852 5308 0818 · +86 176 8871 9572</span><span data-lang="zh">电话：+852 5308 0818 · +86 176 8871 9572</span><span data-lang="en">WeChat: PetterLeeee</span><span data-lang="zh">微信：PetterLeeee</span></div>
    </div>
  </section>
  <p class="foot" data-lang="en">Built for curious people and cautious agents.</p><p class="foot" data-lang="zh">献给好奇的人，也献给懂得谨慎的智能体。</p>
</div>

<script>
(function(){var root=document.getElementById("homeDuo");if(!root)return;var buttons=root.querySelectorAll("[data-language]");function applyLanguage(lang,save){if(lang!=="zh"&&lang!=="en")lang="en";root.setAttribute("data-current-lang",lang);document.documentElement.setAttribute("lang",lang==="zh"?"zh-CN":"en");buttons.forEach(function(b){b.setAttribute("aria-pressed",b.getAttribute("data-language")===lang?"true":"false")});if(save){try{localStorage.setItem("homepage-language",lang)}catch(e){}}}var initial="en";try{var saved=localStorage.getItem("homepage-language");if(saved==="zh"||saved==="en")initial=saved;else if(navigator.language&&navigator.language.toLowerCase().indexOf("zh")===0)initial="zh"}catch(e){if(navigator.language&&navigator.language.toLowerCase().indexOf("zh")===0)initial="zh"}applyLanguage(initial,false);buttons.forEach(function(b){b.addEventListener("click",function(){applyLanguage(b.getAttribute("data-language"),true)})})})();
</script>
