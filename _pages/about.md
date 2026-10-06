---
layout: home
title: 张顺浩
permalink: /
description: 吉林大学计算机科学与技术硕士研究生，关注 AI Agent、后端工程与离线强化学习。
---

<div class="shell">
  <section class="hero" aria-labelledby="hero-title">
    <div>
      <p class="eyebrow">Backend Engineering · AI Agents · Offline RL</p>
      <h1 id="hero-title">张顺浩</h1>
      <div class="hero-actions">
        <a class="button primary" href="mailto:whale_zhang0320@163.com">联系我</a>
        <a class="button secondary" href="https://github.com/whalezhang0320" target="_blank" rel="noreferrer">GitHub ↗</a>
      </div>
    </div>
  </section>

  <section class="quick-facts" aria-label="个人概览">
    <div class="fact"><strong>吉林大学</strong><span>计算机科学与技术 · 硕士</span></div>
    <div class="fact"><strong>腾讯金融科技</strong><span>后台开发 & AI 应用开发</span></div>
    <div class="fact"><strong>研究方向</strong><span>AI Agent · Offline RL</span></div>
  </section>

  <section class="section" id="internship">
    <div class="section-title"><p class="section-kicker">Internship</p><h2>实习经历</h2></div>
    <div class="timeline">
      <article class="entry">
        <p class="entry-date">2026.05 — 2026.09</p>
        <div>
          <h3>腾讯科技（深圳）有限公司</h3>
          <p class="entry-role">后台开发 & AI 应用开发 · 腾讯金融科技</p>
          <ul>
            <li>参与 AI 巡检与根因定位系统建设，将上万条业务曲线收敛至个位数高置信告警，并完善从监控告警到代码行与变更佐证的归因链路。</li>
            <li>为 AI Coding 工作流 FTP 3.0 自研审查 Agent，打通 CR 采集、规则抽取、Skill 沉淀、评测与业务审查，能力复用至 3 套信用卡业务模板。</li>
            <li>设计数币 Plus 小时级补偿链路，以流式捞取、并行筛选、Hash 分片和断点续跑等机制保障大数据量场景下资金不重不漏。</li>
          </ul>
        </div>
      </article>
    </div>
  </section>

  <section class="section" id="education">
    <div class="section-title"><p class="section-kicker">Education</p><h2>学历</h2></div>
    <div class="timeline">
      <article class="entry">
        <p class="entry-date">2024.08 — 至今</p>
        <div>
          <h3>吉林大学</h3>
          <p class="entry-role">计算机科学与技术 · 硕士研究生</p>
          <ul>
            <li>研究方向聚焦离线强化学习与行为策略密度估计。</li>
            <li>获研究生学业奖学金、优秀研究生。</li>
          </ul>
        </div>
      </article>
      <article class="entry">
        <p class="entry-date">2020.09 — 2024.06</p>
        <div>
          <h3>重庆理工大学</h3>
          <p class="entry-role">车辆工程 · 计算机科学与技术辅修</p>
          <ul>
            <li>GPA 3.4 / 5.0，专业前 20%；获国家励志奖学金及多次综合奖学金。</li>
            <li>获车辆工程学院十佳大学生。</li>
          </ul>
        </div>
      </article>
    </div>
  </section>

  <section class="section" id="projects">
    <div class="section-title"><p class="section-kicker">Selected Project</p><h2>项目</h2></div>
    <div class="cards">
      <article class="card">
        <h3>机器学习科研助理 Agent</h3>
        <p class="card-meta">2026.01 — 至今 · FastAPI / Redis / SSE / MCP</p>
        <ul>
          <li>面向科研人员构建论文与代码解析、环境搭建、实验执行、异常诊断和报告生成的一体化 Agent。</li>
          <li>设计代码解析、环境构建、任务配置、训练执行和结果验证的分阶段工作流，支持失败恢复与人工审批。</li>
          <li>通过 MCP 接入 GitHub、Docker、训练平台、日志与 Prometheus，自动生成 Dockerfile 及单机/分布式训练配置。</li>
          <li>建立覆盖依赖冲突、CUDA OOM、NCCL 超时等场景的 Eval 与链路监控。</li>
        </ul>
      </article>
    </div>
  </section>

  <section class="section" id="research">
    <div class="section-title"><p class="section-kicker">Research</p><h2>研究</h2></div>
    <div class="cards">
      <article class="card">
        <h3>Dual Uncertainty Regularization for Offline Reinforcement Learning</h3>
        <p class="card-meta">AAAI 2027 投稿中 · Offline Reinforcement Learning</p>
        <p>结合 Flow-GAN 行为密度建模与 Q 网络集成方差，构建密度加权惩罚：在低密度 OOD 区域增强约束，在高密度 ID 区域缓解过度保守。</p>
        <div class="metric-row" aria-label="研究结果">
          <div class="metric"><strong>+8.1%</strong><span>MuJoCo 总分</span></div>
          <div class="metric"><strong>+33.3%</strong><span>Maze2D 总分</span></div>
          <div class="metric"><strong>−46.1%</strong><span>训练时间</span></div>
        </div>
      </article>
      <article class="card">
        <h3>Non-Parametric Behavior Policy Density Estimation for Offline RL</h3>
        <p class="card-meta">Information Processing & Management 投稿中 · CCF-B</p>
        <p>使用核密度估计直接建模状态条件下的行为策略密度，并结合高斯核与状态自适应带宽，为 OOD 动作识别及价值正则化提供稳定的密度信号。</p>
        <div class="metric-row" aria-label="研究结果">
          <div class="metric"><strong>+4.1%</strong><span>MuJoCo 总分</span></div>
          <div class="metric"><strong>+9.7%</strong><span>Maze2D 总分</span></div>
          <div class="metric"><strong>KDE</strong><span>非参数密度估计</span></div>
        </div>
      </article>
    </div>
  </section>

  <section class="section" id="skills">
    <div class="section-title"><p class="section-kicker">Toolkit</p><h2>技术栈</h2></div>
    <div class="skills-grid">
      <div class="skill-group"><h3>编程语言</h3><p>Go · Python · Java</p></div>
      <div class="skill-group"><h3>后端工程</h3><p>Gin · GORM · gRPC · Kafka</p></div>
      <div class="skill-group"><h3>数据与基础设施</h3><p>Redis · MySQL · Docker · Prometheus</p></div>
    </div>
  </section>
</div>
