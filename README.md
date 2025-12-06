## 🎥 Car Wash Queue Animation (FIFO)

<svg width="700" height="140" viewBox="0 0 700 140" xmlns="http://www.w3.org/2000/svg">

  <!-- Road -->
  <rect x="50" y="40" width="600" height="60" rx="10"
        fill="#ffffff" stroke="#333" stroke-width="3"
        stroke-dasharray="8 6"/>

  <!-- Labels -->
  <text x="55" y="30" font-size="12" font-family="Arial" fill="#000">
    Front (Dequeue)
  </text>
  <text x="560" y="30" font-size="12" font-family="Arial" fill="#000">
    Rear (Enqueue)
  </text>

  <!-- Car 1 -->
  <g>
    <rect y="55" width="70" height="30" rx="6" fill="#3498db"/>
    <text x="15" y="75" fill="white" font-size="12">Car1</text>
    <animateTransform attributeName="transform" type="translate"
      from="650 0" to="60 0" dur="1s" begin="0s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate"
      from="60 0" to="-120 0" dur="1s" begin="3s" fill="freeze"/>
  </g>

  <!-- Car 2 -->
  <g>
    <rect y="55" width="70" height="30" rx="6" fill="#2ecc71"/>
    <text x="15" y="75" fill="white" font-size="12">Car2</text>
    <animateTransform attributeName="transform" type="translate"
      from="650 0" to="140 0" dur="1s" begin="0.5s" fill="freeze"/>
    <animateTransform attributeName="transform" type="translate"
      from="140 0" to="-120 0" dur="1s" begin="4s" fill="freeze"/>
  </g>

  <!-- Car 3 -->
  <g>
    <rect y="55" width="70" height="30" rx="6" fill="#e67e22"/>
    <text x="15" y="75" fill="white" font-size="12">Car3</text>
    <animateTransform attributeName="transform" type="translate"
      from="650 0" to="220 0" dur="1s" begin="1s" fill="freeze"/>
  </g>

  <!-- Car 4 -->
  <g>
    <rect y="55" width="70" height="30" rx="6" fill="#9b59b6"/>
    <text x="15" y="75" fill="white" font-size="12">Car4</text>
    <animateTransform attributeName="transform" type="translate"
      from="650 0" to="300 0" dur="1s" begin="2s" fill="freeze"/>
  </g>

</svg>

🟦 **Blue cars enter from the rear → queue builds**  
⬅️ **Cars leave from the front → washing begins**  
✅ **First-In, First-Out (FIFO) behavior**
