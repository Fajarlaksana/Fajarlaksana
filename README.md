<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 230" width="100%">
<defs>
  <pattern id="pg" width="8" height="8" patternUnits="userSpaceOnUse">
    <path d="M 8 0 L 0 0 0 8" fill="none" stroke="rgba(0,255,136,0.06)" stroke-width="0.5"/>
  </pattern>
</defs>

<!-- Background -->
<rect width="800" height="230" fill="#060612"/>
<rect width="800" height="230" fill="url(#pg)"/>

<!-- Scanline sweep -->
<rect width="800" height="3" fill="rgba(0,255,136,0.08)" y="0">
  <animate attributeName="y" from="-3" to="233" dur="5s" repeatCount="indefinite"/>
</rect>

<!-- Frame border -->
<rect x="6" y="6" width="788" height="218" fill="none" stroke="rgba(0,255,136,0.2)" stroke-width="1"/>

<!-- Corner TL -->
<rect x="6"   y="6"   width="28" height="4"  fill="#00ff88"/>
<rect x="6"   y="6"   width="4"  height="28" fill="#00ff88"/>
<rect x="18"  y="18"  width="4"  height="4"  fill="#00ff88" opacity="0.3"/>
<!-- Corner TR -->
<rect x="766" y="6"   width="28" height="4"  fill="#00ff88"/>
<rect x="790" y="6"   width="4"  height="28" fill="#00ff88"/>
<rect x="778" y="18"  width="4"  height="4"  fill="#00ff88" opacity="0.3"/>
<!-- Corner BL -->
<rect x="6"   y="220" width="28" height="4"  fill="#00ff88"/>
<rect x="6"   y="196" width="4"  height="28" fill="#00ff88"/>
<rect x="18"  y="208" width="4"  height="4"  fill="#00ff88" opacity="0.3"/>
<!-- Corner BR -->
<rect x="766" y="220" width="28" height="4"  fill="#00ff88"/>
<rect x="790" y="196" width="4"  height="28" fill="#00ff88"/>
<rect x="778" y="208" width="4"  height="4"  fill="#00ff88" opacity="0.3"/>

<!-- Stars (SMIL twinkle) -->
<rect x="55"  y="24"  width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.9;0.05;0.9" dur="2.4s" repeatCount="indefinite"/></rect>
<rect x="115" y="46"  width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.1;0.95;0.1" dur="3.2s" repeatCount="indefinite"/></rect>
<rect x="185" y="19"  width="3" height="3" fill="#fff"><animate attributeName="opacity" values="0.7;0.05;0.7" dur="1.8s" repeatCount="indefinite"/></rect>
<rect x="268" y="38"  width="2" height="2" fill="#00d4ff"><animate attributeName="opacity" values="0.9;0.1;0.9" dur="2.1s" repeatCount="indefinite"/></rect>
<rect x="335" y="22"  width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="3.5s" repeatCount="indefinite"/></rect>
<rect x="415" y="44"  width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.8;0.05;0.8" dur="2.7s" repeatCount="indefinite"/></rect>
<rect x="496" y="27"  width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.1;0.85;0.1" dur="1.9s" repeatCount="indefinite"/></rect>
<rect x="562" y="15"  width="3" height="3" fill="#fff"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="4.0s" repeatCount="indefinite"/></rect>
<rect x="625" y="40"  width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.9;0.05;0.9" dur="2.2s" repeatCount="indefinite"/></rect>
<rect x="704" y="24"  width="2" height="2" fill="#00d4ff"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="3.0s" repeatCount="indefinite"/></rect>
<rect x="80"  y="157" width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.6;0.05;0.6" dur="2.6s" repeatCount="indefinite"/></rect>
<rect x="735" y="150" width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.1;0.8;0.1" dur="1.7s" repeatCount="indefinite"/></rect>
<rect x="382" y="52"  width="2" height="2" fill="#ff88cc"><animate attributeName="opacity" values="0.8;0.1;0.8" dur="3.3s" repeatCount="indefinite"/></rect>
<rect x="455" y="17"  width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="2.0s" repeatCount="indefinite"/></rect>
<rect x="158" y="160" width="2" height="2" fill="#fff"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="2.9s" repeatCount="indefinite"/></rect>

<!-- PLAYER 1 label -->
<text x="20" y="28" font-family="Courier New, monospace" font-size="11" fill="#ffff00" letter-spacing="2">&#x25B6; PLAYER 1</text>

<!-- LVL top right -->
<text x="780" y="21" font-family="Courier New, monospace" font-size="10" fill="#ff6eb4" letter-spacing="1" text-anchor="end">LVL &#x2605; 99</text>
<text x="780" y="34" font-family="Courier New, monospace" font-size="10" fill="#ff6eb4" letter-spacing="1" text-anchor="end">FULL STACK</text>

<!-- HP bar -->
<text x="20" y="180" font-family="Courier New, monospace" font-size="9" fill="#444" letter-spacing="1">HP</text>
<rect x="38" y="170" width="132" height="7" fill="rgba(0,255,136,0.12)"/>
<rect x="38" y="170" width="0" height="7" fill="#00ff88">
  <animate attributeName="width" from="0" to="132" dur="2s" fill="freeze" repeatCount="1"/>
</rect>

<!-- MP bar -->
<text x="20" y="196" font-family="Courier New, monospace" font-size="9" fill="#444" letter-spacing="1">MP</text>
<rect x="38" y="186" width="132" height="7" fill="rgba(0,212,255,0.12)"/>
<rect x="38" y="186" width="0" height="7" fill="#00d4ff">
  <animate attributeName="width" from="0" to="82" dur="2.5s" fill="freeze" repeatCount="1"/>
</rect>

<!-- EXP -->
<text x="20" y="212" font-family="Courier New, monospace" font-size="9" fill="#333">EXP &#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2588;&#x2591;&#x2591;&#x2591;</text>

<!-- Main title (float up/down + glow) -->
<text font-family="Courier New, monospace" font-size="40" font-weight="bold" text-anchor="middle" letter-spacing="8" x="400">
  <animate attributeName="y" values="100;94;100" dur="3.2s" repeatCount="indefinite"/>
  <animate attributeName="fill" values="#00ff88;#ccffdd;#00ff88" dur="2.2s" repeatCount="indefinite"/>
  FAJAR LAKSANA
</text>

<!-- Subtitle -->
<text font-family="Courier New, monospace" font-size="12" text-anchor="middle" letter-spacing="3" x="400">
  <animate attributeName="y" values="126;120;126" dur="3.2s" repeatCount="indefinite"/>
  <animate attributeName="fill" values="#00d4ff;#aaeeff;#00d4ff" dur="3s" repeatCount="indefinite"/>
  FULL STACK &#xB7; DESIGNER &#xB7; FINTECH EXPLORER
</text>

<!-- Blinking cursor -->
<text x="626" font-family="Courier New, monospace" font-size="12" fill="#00d4ff">
  <animate attributeName="y" values="126;120;126" dur="3.2s" repeatCount="indefinite"/>
  <animate attributeName="opacity" values="1;1;0;0;1" dur="1.1s" repeatCount="indefinite"/>
  &#x2588;
</text>

<!-- PRESS START blinking -->
<text x="400" y="153" font-family="Courier New, monospace" font-size="11" fill="#ffff00" text-anchor="middle" letter-spacing="4">
  <animate attributeName="opacity" values="1;1;0;0;1" dur="1.2s" repeatCount="indefinite"/>
  &#x25B6; PRESS START &#x25C0;
</text>

<!-- Walking pixel character -->
<g>
  <animateTransform attributeName="transform" type="translate" from="-90 0" to="890 0" dur="8s" repeatCount="indefinite"/>
  <!-- Shadow -->
  <ellipse cx="11" cy="218" rx="13" ry="2.5" fill="rgba(0,0,0,0.35)"/>
  <!-- Hat -->
  <rect x="3"  y="167" width="16" height="3"  fill="#1a1a2e"/>
  <rect x="1"  y="170" width="20" height="3"  fill="#2a2a4e"/>
  <!-- Head -->
  <rect x="3"  y="173" width="16" height="12" fill="#f5c088"/>
  <!-- Eyes -->
  <rect x="5"  y="177" width="4"  height="3"  fill="#222"/>
  <rect x="13" y="177" width="4"  height="3"  fill="#222"/>
  <!-- Mouth -->
  <rect x="7"  y="183" width="8"  height="2"  fill="#c07050"/>
  <!-- Body -->
  <rect x="1"  y="185" width="20" height="13" fill="#3355cc"/>
  <rect x="7"  y="187" width="8"  height="2"  fill="#2244aa"/>
  <!-- Left arm (swings) -->
  <rect x="-3" y="186" width="4" height="9" fill="#f5c088">
    <animate attributeName="y" values="186;190;186" dur="0.38s" repeatCount="indefinite"/>
  </rect>
  <!-- Right arm (swings opposite) -->
  <rect x="21" y="190" width="4" height="9" fill="#f5c088">
    <animate attributeName="y" values="190;186;190" dur="0.38s" repeatCount="indefinite"/>
  </rect>
  <!-- Left leg -->
  <rect x="2"  y="198" width="7" height="10" fill="#223388">
    <animate attributeName="y" values="198;193;198" dur="0.38s" repeatCount="indefinite"/>
  </rect>
  <rect x="1"  y="207" width="9" height="4" fill="#111">
    <animate attributeName="y" values="207;202;207" dur="0.38s" repeatCount="indefinite"/>
  </rect>
  <!-- Right leg (opposite phase) -->
  <rect x="13" y="193" width="7" height="10" fill="#223388">
    <animate attributeName="y" values="193;198;193" dur="0.38s" repeatCount="indefinite"/>
  </rect>
  <rect x="12" y="202" width="9" height="4" fill="#111">
    <animate attributeName="y" values="202;207;202" dur="0.38s" repeatCount="indefinite"/>
  </rect>
</g>

</svg>
