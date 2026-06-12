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

