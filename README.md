
<style>
  .gh { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; color: var(--color-text-primary); max-width: 680px; }
  .gh h1 { font-size: 22px; font-weight: 500; margin: 0 0 4px; }
  .gh h2 { font-size: 16px; font-weight: 500; margin: 1.5rem 0 0.75rem; border-bottom: 0.5px solid var(--color-border-tertiary); padding-bottom: 6px; }
  .badge { display: inline-block; background: #0d1117; color: #58a6ff; font-size: 12px; padding: 3px 10px; border-radius: 4px; margin: 3px 2px; border: 0.5px solid #30363d; }
  .badge.green { background: #0d1117; color: #3fb950; }
  .badge.orange { background: #0d1117; color: #d29922; }
  .badge.red { background: #0d1117; color: #f85149; }
  .stat-row { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin: 0.75rem 0; }
  .stat-card { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 12px 14px; }
  .stat-card .label { font-size: 12px; color: var(--color-text-secondary); margin-bottom: 4px; }
  .stat-card .value { font-size: 18px; font-weight: 500; }
  .pill { display: inline-block; background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: 20px; padding: 3px 12px; font-size: 13px; margin: 3px 2px; }
  .typing { display: inline-block; border-right: 2px solid var(--color-text-primary); padding-right: 2px; white-space: nowrap; overflow: hidden; animation: typing 3.5s steps(40, end) infinite, blink 0.75s step-end infinite; width: 0; }
  @keyframes typing { 0%,10% { width: 0 } 50%,90% { width: 26ch } 100% { width: 0 } }
  @keyframes blink { from,to { border-color: transparent } 50% { border-color: var(--color-text-primary) } }
  .snake-row { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 10px 14px; font-size: 13px; color: var(--color-text-secondary); display:flex; align-items:center; gap:8px; }
</style>
<div class="gh" style="padding: 1rem 0;">
  <h2 style="sr-only">GitHub profile README preview</h2>

  <div style="display:flex; align-items:center; gap:14px; margin-bottom:1rem;">
    <div style="width:56px;height:56px;border-radius:50%;background:var(--color-background-info);display:flex;align-items:center;justify-content:center;font-size:22px;font-weight:500;color:var(--color-text-info);">AP</div>
    <div>
      <h1>Hi, I'm Aditya Patel <span style="font-size:22px;">👋</span></h1>
      <p style="margin:0;font-size:14px;color:var(--color-text-secondary);">
        <span class="typing">☕ Java Developer | 3 Years of Experience</span>
      </p>
    </div>
  </div>

  <p style="font-size:14px;line-height:1.7;margin:0 0 1rem;">
    Passionate backend developer with <strong style="font-weight:500;">3 years</strong> of hands-on experience building robust, scalable Java applications.
    I specialize in <strong style="font-weight:500;">Spring Boot</strong> microservices, RESTful APIs, and cloud-native architectures.
    I love writing clean, maintainable code and solving complex backend challenges.
  </p>

  <h2><i class="ti ti-code" aria-hidden="true"></i> Tech stack</h2>
  <div style="margin-bottom:0.5rem;">
    <strong style="font-size:13px;color:var(--color-text-secondary);">Core</strong><br>
    <span class="badge">Java 17+</span>
    <span class="badge">Spring Boot</span>
    <span class="badge">Spring MVC</span>
    <span class="badge">Spring Security</span>
    <span class="badge">Hibernate / JPA</span>
  </div>
  <div style="margin-bottom:0.5rem;">
    <strong style="font-size:13px;color:var(--color-text-secondary);">Architecture</strong><br>
    <span class="badge green">Microservices</span>
    <span class="badge green">REST APIs</span>
    <span class="badge green">Apache Kafka</span>

  </div>
  <div style="margin-bottom:0.5rem;">
    <strong style="font-size:13px;color:var(--color-text-secondary);">Databases</strong><br>
    <span class="badge orange">MySQL</span>
  </div>
  <div>
    <strong style="font-size:13px;color:var(--color-text-secondary);">Tools & Cloud</strong><br>
    <span class="badge red">Git</span>
    <span class="badge red">Maven</span>
    <span class="badge red">AWS</span>
    <span class="badge red">Jenkins</span>
    <span class="badge red">IntelliJ IDEA</span>
  </div>

  <h2><i class="ti ti-chart-bar" aria-hidden="true"></i> At a glance</h2>
  <div class="stat-row">
    <div class="stat-card"><div class="label">Experience</div><div class="value">3 Years</div></div>
    <div class="stat-card"><div class="label">Specialization</div><div class="value">Backend / Java</div></div>
  </div>

  <h2><i class="ti ti-flame" aria-hidden="true"></i> Currently</h2>
  <div style="display:flex;flex-wrap:wrap;gap:8px;">
    <span class="pill">🔭 Building microservices with Spring Boot</span>
    <span class="pill">💬 Ask me about Java, Spring, APIs</span>
	<span class="pill">📫 Reach me at: [Adityapatel200308@gmail.com]</span>
  </div>

  

  <p style="font-size:12px;color:var(--color-text-secondary);margin-top:1rem;text-align:center;">↑ Preview of your profile README · actual page uses GitHub's markdown renderer</p>
</div>
