
```aura width=800 height=220
<div style={{ display: 'flex', flexDirection: 'row', gap: 16, width: '100%', height: '100%', fontFamily: '"Bebas Neue", Impact, sans-serif', letterSpacing: 1 }}>
  <style>{`
    @keyframes about-orb-l { 0%, 100% { transform: translate(0,0); opacity: 0.65; } 50% { transform: translate(20px,-14px); opacity: 0.9; } }
    @keyframes about-orb-r { 0%, 100% { transform: translate(0,0); opacity: 0.55; } 50% { transform: translate(-16px,12px); opacity: 0.8; } }
    @keyframes about-ring { 0%, 100% { opacity: 0.07; } 50% { opacity: 0.2; } }
    @keyframes about-ring-b { 0%, 100% { opacity: 0.04; } 50% { opacity: 0.13; } }
    @keyframes cursor-blink { 0%, 100% { opacity: 1; } 49% { opacity: 1; } 50% { opacity: 0; } 99% { opacity: 0; } }
    #ab-o1 { animation: about-orb-l 8s ease-in-out infinite; }
    #ab-o2 { animation: about-orb-r 10s ease-in-out infinite 1s; }
    #ab-o3 { animation: about-orb-l 7s ease-in-out infinite 2s; }
    #ab-r1 { animation: about-ring 7s ease-in-out infinite; }
    #ab-r2 { animation: about-ring 7s ease-in-out infinite 2s; }
    #ab-r3 { animation: about-ring-b 7s ease-in-out infinite 3.5s; }
    #ab-cursor { animation: cursor-blink 1.1s step-end infinite; }
  `}</style>

  <div style={{ position: 'relative', display: 'flex', flex: 1, height: '100%', background: '#08080d', borderRadius: 16, overflow: 'hidden' }}>
    <img src="https://www.cjoint.com/doc/22_10/LJhx05V3V6O_le-thousand-sunny-fond-decran-anime-de-one-piece.gif" style={{ position: 'absolute', top: 0, left: 0, width: '100%', height: '100%', objectFit: 'cover', opacity: 0.35 }} />
    
    <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', justifyContent: 'center', padding: '0 28px', zIndex: 10 }}>
      <span style={{ fontSize: 11, color: 'rgba(255,255,255,0.35)', letterSpacing: 3, textTransform: 'uppercase', marginBottom: 10 }}> Software Engineer · DevOps · SRE </span>
      <span style={{ fontSize: 36, color: '#ffffff', lineHeight: 1.1, letterSpacing: 2 }}>Hi, I'm Ashmit</span>
      <span style={{ fontSize: 18, color: 'rgba(255,255,255,0.95)', maxWidth: 520, marginTop: 12, lineHeight: 1.4 }}>
        Delivering scalable DevOps and SRE solutions through container pipelines and infra automation.
      </span>
      <div style={{ display: 'flex', flexWrap: 'wrap', gap: 10, marginTop: 16, maxWidth: 520 }}>
        <a href="https://www.credly.com/badges/d884d83b-c5ae-43d4-b4bc-0c9e77e7f646/public_url" target="_blank" rel="noopener noreferrer" style={{ textDecoration: 'none', fontSize: 11, fontWeight: 600, color: '#ff6666', padding: '6px 14px', background: 'rgba(255,102,102,0.1)', border: '1px solid rgba(255,102,102,0.25)', borderRadius: 999, display: 'flex', alignItems: 'center', gap: 6 }}>
          <img src="https://skillicons.dev/icons?i=redhat" width={14} height={14} /> RHCSA Certified
        </a>
        <span style={{ fontSize: 11, fontWeight: 600, color: '#66b3ff', padding: '6px 14px', background: 'rgba(102,179,255,0.1)', border: '1px solid rgba(102,179,255,0.25)', borderRadius: 999, display: 'flex', alignItems: 'center', gap: 6 }}>
          💧 Intern @ Bisleri
        </span>
        <span style={{ fontSize: 11, color: 'rgba(255,255,255,0.7)', padding: '6px 14px', background: 'rgba(255,255,255,0.03)', border: '1px solid rgba(255,255,255,0.1)', borderRadius: 999 }}>
          DevOps & SRE
        </span>
      </div>
    </div>
  </div>

  <div style={{ display: 'flex', flexDirection: 'column', gap: 16, width: 220, flexShrink: 0 }}>
    <a href="https://www.credly.com/badges/d884d83b-c5ae-43d4-b4bc-0c9e77e7f646/public_url" target="_blank" rel="noopener noreferrer" style={{ textDecoration: 'none', position: 'relative', display: 'flex', flex: 1, background: '#08080d', borderRadius: 16, overflow: 'hidden', alignItems: 'center', justifyContent: 'center' }}>
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvpM2tPhtH3St6_pviw5Py01EywWEjmT3P_cFRNrWLew&s=10" style={{ position: 'absolute', top: 0, left: 0, width: '100%', height: '100%', objectFit: 'cover', opacity: 0.3 }} />
      <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10 }}>
       
        <span style={{ fontWeight: 700,fontSize: 11, color: 'rgba(255,255,255,0.4)', letterSpacing: 2, textTransform: 'uppercase', marginTop: 4 }}>REDHATTER</span>
      </div>
    </a>
    <div style={{ position: 'relative', display: 'flex', flex: 1, background: '#08080d', borderRadius: 16, overflow: 'hidden', alignItems: 'center', justifyContent: 'center' }}>
      <img src="https://img.artpal.com/893313/10-24-6-6-20-45-20m.jpg" style={{ position: 'absolute', top: 0, left: 0, width: '100%', height: '100%', objectFit: 'cover', opacity: 0.3 }} />
      <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10 }}>
        
        <span style={{ fontSize: 11, color: 'rgba(255,255,255,0.4)', letterSpacing: 2, textTransform: 'uppercase', marginTop: 4 }}>craft matters</span>
      </div>
    </div>
  </div>
</div>
```

```aura width=800 height=250
(function() {
  var categories = [
    { 
      title: 'Languages', color: '#a78bfa', 
      type: 'icons', items: ['cpp', 'py', 'ts', 'js', 'solidity', 'java', 'postgres'] 
    },
    { 
      title: 'Frameworks', color: '#60a5fa', 
      type: 'mixed', 
      icons: ['nextjs', 'react', 'nodejs', 'express', 'fastapi'],
      badges: [
        { name: 'Ethereum', color: '3C3C3D', logo: 'Ethereum', logoColor: 'white' },
        { name: 'Hardhat', color: 'FFF100', logo: 'Hardhat', logoColor: 'black' },
        { name: 'Web3.js', color: 'F16822', logo: 'Web3.js', logoColor: 'white' },
        { name: 'Ethers.js', color: '272A2E', logo: 'ethers', logoColor: 'white' },
      ]
    },
    { 
      title: 'DevOps & Data', color: '#f59e0b', 
      type: 'mixed', 
      icons: ['mongodb', 'mysql', 'supabase', 'linux', 'kubernetes', 'docker', 'redhat', 'git', 'prometheus', 'grafana'],
      badges: [
        { name: 'Snowflake', color: '29B5E8', logo: 'Snowflake', logoColor: 'white' },
        { name: 'dbt', color: 'FF694B', logo: 'dbt', logoColor: 'white' },
        { name: 'Neo4j', color: '015896', logo: 'Neo4j', logoColor: 'white' },
        { name: 'Temporal', color: '242526', logo: 'Temporal', logoColor: 'white' },
      ]
    },
  ];

  return (
    <div style={{
      width: '100%', height: '100%',
      background: '#161616',
      display: 'flex', flexDirection: 'column',
      fontFamily: 'Manrope', padding: '18px 32px', gap: 14,
      borderRadius: 16, border: '1px solid rgba(110,80,220,0.18)',
      position: 'relative', overflow: 'hidden',
    }}>
      <img src="https://wallpapers.com/images/featured/one-piece-wano-4k-nxznpz3omqzsc5yk.jpg" width={860} height={260} style={{ position: 'absolute', top: 0, left: 0, width: '100%', height: '100%', objectFit: 'cover', opacity: 0.18 }} />

      <style>
        {`
          @keyframes float-slow {
            0%, 100% { transform: translateX(0px); opacity: 0.8; }
            50% { transform: translateX(350px); opacity: 1.2; }
          }
          @keyframes float-medium {
            0%, 100% { transform: translateX(0px); opacity: 0.7; }
            50% { transform: translateX(-250px); opacity: 1.1; }
          }
          @keyframes float-fast {
            0%, 100% { transform: translateX(0px); opacity: 0.9; }
            50% { transform: translateX(200px); opacity: 0.6; }
          }
          @keyframes float-diagonal {
            0%, 100% { transform: translate(0px, 0px); opacity: 0.75; }
            50% { transform: translate(120px, 30px); opacity: 1.0; }
          }
          @keyframes float-wave {
            0%, 100% { transform: translateX(0px); opacity: 0.65; }
            33% { transform: translateX(-160px); opacity: 0.9; }
            66% { transform: translateX(80px); opacity: 1.0; }
          }
          @keyframes float-pulse {
            0%, 100% { transform: scale(1); opacity: 0.8; }
            50% { transform: scale(1.3); opacity: 0.4; }
          }
     
     @keyframes float-ember-1 {
       0% { transform: translate(0, 0) scale(1); opacity: 0; }
       20% { opacity: 1; }
       80% { opacity: 1; }
       100% { transform: translate(-20px, -60px) scale(0.5); opacity: 0; }
     }
     @keyframes float-ember-2 {
       0% { transform: translate(0, 0) scale(1); opacity: 0; }
       20% { opacity: 1; }
       80% { opacity: 1; }
       100% { transform: translate(20px, -80px) scale(0.6); opacity: 0; }
     }
     @keyframes float-ember-3 {
       0% { transform: translate(0, 0) scale(1); opacity: 0; }
       20% { opacity: 0.8; }
       80% { opacity: 0.8; }
       100% { transform: translate(-10px, -50px) scale(0.4); opacity: 0; }
     }
     #ember-1 { animation: float-ember-1 3s ease-in infinite; }
     #ember-2 { animation: float-ember-2 4s ease-in infinite; animation-delay: 1s; }
     #ember-3 { animation: float-ember-3 2.5s ease-in infinite; animation-delay: 2s; }
     #ember-4 { animation: float-ember-1 3.5s ease-in infinite; animation-delay: 0.5s; }
     #ember-5 { animation: float-ember-2 4.5s ease-in infinite; animation-delay: 1.5s; }
     #glow-1 { animation: float-slow 9s ease-in-out infinite; }
          #glow-2 { animation: float-medium 12s ease-in-out infinite; }
          #glow-3 { animation: float-fast 8s ease-in-out infinite; }
          #glow-4 { animation: float-diagonal 11s ease-in-out infinite reverse; }
          #glow-5 { animation: float-wave 14s ease-in-out infinite reverse; }
          #glow-6 { animation: float-pulse 6s ease-in-out infinite; }
        `}
      </style>

      <div style={{ display:'flex', fontSize:10, fontWeight:700, color:'rgba(155,140,210,0.5)', letterSpacing:'3px' }}>
        TECH STACK
      </div>
      <div style={{ display:'flex', flexDirection:'column', gap:8 }}>
        {categories.map(function(cat) {
          return (
            <div key={cat.title} style={{ display:'flex', alignItems:'flex-start', gap:8, minHeight: 52 }}>
              <div style={{ display:'flex', fontSize:10, fontWeight:700, color:cat.color, letterSpacing:'1px', width:130, minWidth:130 }}>
                {cat.title.toUpperCase()}
              </div>
              <div style={{ display:'flex', flexWrap:'wrap', gap:7, alignItems:'center' }}>
                {cat.type === 'icons' && cat.items.map(function(item) {
                  return (
                    <img key={item} src={'https://skillicons.dev/icons?i=' + item} width={40} height={40} style={{ borderRadius: 8 }} />
                  );
                })}
                {cat.type === 'mixed' && (
                  <div style={{ display:'flex', flexWrap:'wrap', gap:7, alignItems:'center' }}>
                    {cat.icons.map(function(item) {
                      return (
                        <img key={item} src={'https://skillicons.dev/icons?i=' + item} width={40} height={40} style={{ borderRadius: 8 }} />
                      );
                    })}
                    {cat.badges.map(function(b) {
                      return (
                        <img key={b.name} src={'https://img.shields.io/badge/' + b.name + '-' + b.color + '?style=for-the-badge&logo=' + b.logo + '&logoColor=' + b.logoColor} width={120} height={28} style={{ borderRadius: 4, marginLeft: 4 }} />
                      );
                    })}
                  </div>
                )}
              </div>
            </div>
          );
        })}
      </div>
    </div>
  );
})()
```




```aura width=800 height=280
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%', background: '#08080d', borderRadius: 20, overflow: 'hidden', fontFamily: 'Inter, sans-serif' }}>
  <style>{`
    @keyframes orb-a { 0%, 100% { transform: translate(0, 0); opacity: 0.6; } 50% { transform: translate(28px, -22px); opacity: 0.9; } }
    @keyframes orb-b { 0%, 100% { transform: translate(0, 0); opacity: 0.5; } 50% { transform: translate(-22px, 18px); opacity: 0.75; } }
    @keyframes orb-c { 0%, 100% { transform: translate(0, 0); opacity: 0.35; } 50% { transform: translate(16px, -28px); opacity: 0.6; } }
    @keyframes ring-blink { 0%, 100% { opacity: 0.06; } 50% { opacity: 0.18; } }
    @keyframes ring-blink-b { 0%, 100% { opacity: 0.04; } 50% { opacity: 0.12; } }
    @keyframes dot-spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
    #hero-o1 { animation: orb-a 9s ease-in-out infinite; }
    #hero-o2 { animation: orb-b 11s ease-in-out infinite 0.8s; }
    #hero-o3 { animation: orb-a 8s ease-in-out infinite 2s; }
    #hero-o4 { animation: orb-b 13s ease-in-out infinite 0.4s; }
    #hero-o5 { animation: orb-c 7s ease-in-out infinite 1.2s; }
    #hr1 { animation: ring-blink 8s ease-in-out infinite; }
    #hr2 { animation: ring-blink 8s ease-in-out infinite 1.4s; }
    #hr3 { animation: ring-blink-b 8s ease-in-out infinite 2.8s; }
    #hr4 { animation: ring-blink-b 8s ease-in-out infinite 4.2s; }
    #hr5 { animation: ring-blink-b 10s ease-in-out infinite 5.6s; }
    #hero-dot { animation: dot-spin 20s linear infinite; }
  `}</style>

  <svg width="800" height="280" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="hg1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(108,195,130,0.55)" />
        <stop offset="100%" stopColor="rgba(108,195,130,0)" />
      </radialGradient>
      <radialGradient id="hg2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(230,100,115,0.5)" />
        <stop offset="100%" stopColor="rgba(230,100,115,0)" />
      </radialGradient>
      <radialGradient id="hg3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(195,155,255,0.35)" />
        <stop offset="100%" stopColor="rgba(195,155,255,0)" />
      </radialGradient>
      <radialGradient id="hg4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(255,195,110,0.28)" />
        <stop offset="100%" stopColor="rgba(255,195,110,0)" />
      </radialGradient>
      <radialGradient id="hg5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(80,160,220,0.3)" />
        <stop offset="100%" stopColor="rgba(80,160,220,0)" />
      </radialGradient>
    </defs>
    <ellipse id="hero-o1" cx="110" cy="240" rx="260" ry="200" fill="url(#hg1)" />
    <ellipse id="hero-o2" cx="710" cy="55" rx="230" ry="190" fill="url(#hg2)" />
    <ellipse id="hero-o3" cx="620" cy="260" rx="200" ry="160" fill="url(#hg3)" />
    <ellipse id="hero-o4" cx="200" cy="40" rx="190" ry="150" fill="url(#hg4)" />
    <ellipse id="hero-o5" cx="400" cy="270" rx="170" ry="130" fill="url(#hg5)" />
    <circle id="hr1" cx="400" cy="140" r="52"  fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <circle id="hr2" cx="400" cy="140" r="92"  fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <circle id="hr3" cx="400" cy="140" r="138" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <circle id="hr4" cx="400" cy="140" r="192" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <circle id="hr5" cx="400" cy="140" r="256" fill="none" stroke="rgba(255,255,255,0.9)" strokeWidth="0.7" />
    <g id="hero-dot">
      <circle cx="400" cy="88" r="2.5" fill="rgba(255,255,255,0.5)" />
    </g>
  </svg>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 10 }}>
    <span style={{ fontSize: 60, fontWeight: 700, color: '#ffffff', letterSpacing: -2, lineHeight: 1 }}>{(github && github.user && (github.user.name || github.user.login)) || 'GitHub Developer'}</span>
    <span style={{ fontSize: 13, color: 'rgba(255,255,255,0.4)', marginTop: 16, letterSpacing: 5, textTransform: 'uppercase', fontWeight: 300 }}>design · code · create</span>
    <div style={{ display: 'flex', gap: 8, marginTop: 30 }}>
      <span style={{ padding: '5px 16px', background: 'rgba(255,255,255,0.04)', color: 'rgba(255,255,255,0.55)', borderRadius: 100, fontSize: 11, border: '1px solid rgba(255,255,255,0.09)', letterSpacing: 1 }}>minimalism</span>
      <span style={{ padding: '5px 16px', background: 'rgba(255,255,255,0.04)', color: 'rgba(255,255,255,0.55)', borderRadius: 100, fontSize: 11, border: '1px solid rgba(255,255,255,0.09)', letterSpacing: 1 }}>open source</span>
      <span style={{ padding: '5px 16px', background: 'rgba(255,255,255,0.04)', color: 'rgba(255,255,255,0.55)', borderRadius: 100, fontSize: 11, border: '1px solid rgba(255,255,255,0.09)', letterSpacing: 1 }}>web</span>
    </div>
  </div>
</div>

```