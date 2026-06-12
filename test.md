```aura width=200 height=100
<div style={{display:'flex'}}>
  <style>{`
    @keyframes scroll { from { transform: translateX(0); } to { transform: translateX(-100px); } }
    svg > svg.track { animation: scroll 10s linear infinite; }
  `}</style>
  <svg className="track" width="200" height="50" viewBox="0 0 200 50">
    <div style={{display:'flex', width:10, height:10, backgroundColor:'red'}}></div>
  </svg>
</div>
```
