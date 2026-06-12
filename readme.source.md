```aura width=860 height=240
<div style={{
  width:'100%',
  height:'100%',
  background:'#06060f',
  borderRadius:18,
  border:'1px solid rgba(160,120,255,0.22)',
  padding:32,
  display:'flex',
  flexDirection:'column',
  fontFamily:'Inter',
  position:'relative',
  overflow:'hidden'
}}>
  <div style={{
    position:'absolute', width:180, height:180, top:-55, left:-45,
    borderRadius:'50%',
    background:'radial-gradient(circle, rgba(90,50,220,0.13), transparent 70%)'
  }}/>
  <div style={{
    position:'absolute', width:130, height:130, bottom:-35, right:-20,
    borderRadius:'50%',
    background:'radial-gradient(circle, rgba(60,140,255,0.1), transparent 70%)'
  }}/>

  <div style={{fontSize:12, color:'#7a72a8', letterSpacing:2, textTransform:'uppercase', marginBottom:10, fontWeight:600}}>
    Software Engineer · DevOps · SRE
  </div>

  <div style={{fontSize:34, fontWeight:800, color:'#f0ecff', marginBottom:12, letterSpacing:-0.8}}>
    Hi, I'm Ashmit 👋
  </div>

  <div style={{fontSize:15, color:'#9d95c5', lineHeight:1.75}}>
    DevOps and SRE enthusiast focused on Linux, Kubernetes, cloud infrastructure and automation.
    RHCSA certified · Targeting CKA → EX280 → Red Hat SRE.
  </div>

  <div style={{marginTop:18, display:'flex', gap:10, flexWrap:'wrap'}}>
    {[
      '📍 Mumbai, India',
      '🎓 DJ Sanghvi · B.Tech IT · 2027',
      '🏢 Bisleri International · Trainee Engineer'
    ].map(tag => (
      <div style={{
        fontSize:12, color:'#8a82b8',
        background:'rgba(100,60,200,0.1)',
        border:'1px solid rgba(130,90,255,0.18)',
        padding:'5px 13px', borderRadius:20
      }}>
        {tag}
      </div>
    ))}
  </div>
</div>
```

```aura width=860 height=80
<div style={{
  width:'100%',
  height:'100%',
  background:'#0d0b1a',
  borderRadius:18,
  border:'1px solid rgba(140,100,255,0.2)',
  display:'flex',
  alignItems:'center',
  gap:14,
  padding:'0 20px',
  overflow:'hidden',
  fontFamily:'Inter'
}}>
  {[
    ['Linux','#6ef0e8'], ['Red Hat','#ff9090'], ['Kubernetes','#7ab8ff'],
    ['Docker','#c4a8ff'], ['Terraform','#ffd080'], ['Ansible','#7af0a0'],
    ['AWS','#7ab8ff'], ['Python','#f0a8e0'], ['Go','#6ef0e8'],
    ['C++','#c4a8ff'], ['gRPC','#7af0a0'], ['Redis','#ffd080'],
    ['Next.js','#7ab8ff'], ['FastAPI','#f0a8e0'], ['Prometheus','#6ef0e8'], ['Grafana','#c4a8ff']
  ].map(([name,color])=>(
    <div style={{
      display:'flex', alignItems:'center', gap:7,
      padding:'8px 16px', borderRadius:999,
      border:`1px solid ${color}55`,
      color:color,
      fontSize:13, fontWeight:600,
      whiteSpace:'nowrap'
    }}>
      <div style={{width:7,height:7,borderRadius:'50%',background:color}}/>
      {name}
    </div>
  ))}
</div>
```

```aura width=420 height=220
<div style={{
  width:'100%',
  height:'100%',
  background:'#08080c',
  borderRadius:18,
  border:'1px solid rgba(160,120,255,0.22)',
  padding:26,
  display:'flex',
  flexDirection:'column',
  fontFamily:'Inter'
}}>
  <div style={{
    fontSize:21, fontWeight:700, marginBottom:16,
    color:'#c9aaff'
  }}>
    About Me
  </div>
  <div style={{fontSize:15, color:'#9d95c5', lineHeight:1.75}}>
    Interning at Bisleri International on their D2C delivery platform.

    Targeting Cloud/SRE at Red Hat — RHCSA → CKA → EX280 → Go roadmap.

    Building ResuMatch for placements and gRPC/C++ systems work.
  </div>
</div>
```

```aura width=420 height=220
<div style={{
  width:'100%',
  height:'100%',
  background:'#08080c',
  borderRadius:18,
  border:'1px solid rgba(160,120,255,0.22)',
  padding:26,
  display:'flex',
  flexDirection:'column',
  gap:10,
  fontFamily:'Inter'
}}>
  <div style={{fontSize:21, fontWeight:700, marginBottom:6, color:'#c9aaff'}}>
    Certifications
  </div>

  {[
    {icon:'🎖', title:'RHCSA', sub:'Red Hat Linux', status:'285/300', iconBg:'#cc0000', statusColor:'#5de87a', statusBg:'rgba(50,200,100,0.15)'},
    {icon:'⎈', title:'CKA', sub:'Kubernetes Admin', status:'Up next', iconBg:'#326ce5', statusColor:'#b89aff', statusBg:'rgba(160,120,255,0.13)'},
    {icon:'☁', title:'AWS SAA', sub:'Solutions Architect', status:'Planned', iconBg:'#ff9900', statusColor:'#b89aff', statusBg:'rgba(160,120,255,0.13)'}
  ].map(cert=>(
    <div style={{
      display:'flex', alignItems:'center', gap:9,
      padding:'10px 16px',
      background:'rgba(20,12,50,0.5)',
      border:'1px solid rgba(150,110,255,0.28)',
      borderRadius:12
    }}>
      <div style={{
        width:28, height:28, borderRadius:7,
        background:cert.iconBg,
        display:'flex', alignItems:'center', justifyContent:'center',
        fontSize:13
      }}>
        {cert.icon}
      </div>
      <div style={{display:'flex', flexDirection:'column', flex:1}}>
        <div style={{fontSize:13.5, fontWeight:700, color:'#e8e0ff'}}>{cert.title}</div>
        <div style={{fontSize:11, color:'#8a82a8'}}>{cert.sub}</div>
      </div>
      <div style={{
        fontSize:11, fontWeight:500, padding:'2px 8px', borderRadius:20,
        background:cert.statusBg, color:cert.statusColor
      }}>
        {cert.status}
      </div>
    </div>
  ))}
</div>
```

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Smitty-01&show_icons=true&theme=transparent&hide_border=true&title_color=c9aaff&icon_color=8ab4ff&text_color=9d95c5&bg_color=0d0b1a&ring_color=7b5fff&include_all_commits=true&count_private=true" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Smitty-01&layout=compact&theme=transparent&hide_border=true&title_color=c9aaff&text_color=9d95c5&bg_color=0d0b1a&langs_count=8" width="49%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Smitty-01&theme=transparent&hide_border=true&ring=7b5fff&fire=c9aaff&currStreakLabel=8ab4ff&sideLabels=9d95c5&dates=6a6290&stroke=rgba(160,120,255,0.2)&background=0d0b1a&currStreakNum=c9aaff&sideNums=9d95c5" width="100%" />
</p>

---

<p align="center">⚡ Open to collaboration · Always building · Reach out on LinkedIn</p>