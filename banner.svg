<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 200">
  <defs>
    <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#010612"/>
      <stop offset="100%" stop-color="#0b1826"/>
    </linearGradient>
    <linearGradient id="gnd" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#050b16"/>
      <stop offset="100%" stop-color="#020810"/>
    </linearGradient>
    <linearGradient id="cg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#ff8800" stop-opacity="0"/>
      <stop offset="100%" stop-color="#ff7700" stop-opacity="0.13"/>
    </linearGradient>
    <filter id="sg" x="-100%" y="-100%" width="300%" height="300%">
      <feGaussianBlur stdDeviation="13"/>
    </filter>
    <filter id="lg" x="-150%" y="-150%" width="400%" height="400%">
      <feGaussianBlur stdDeviation="5"/>
    </filter>
    <filter id="ng" x="-150%" y="-150%" width="400%" height="400%">
      <feGaussianBlur stdDeviation="3"/>
    </filter>
  </defs>

  <style>
    @keyframes walk { from{transform:translateX(-90px)} to{transform:translateX(980px)} }
    @keyframes fa   { 0%,49%{opacity:1} 50%,100%{opacity:0} }
    @keyframes fb   { 0%,49%{opacity:0} 50%,100%{opacity:1} }
    @keyframes tw   { 0%,100%{opacity:var(--o,.8)} 50%{opacity:calc(var(--o,.8)*.08)} }
    @keyframes shoot {
      0%,1%  { opacity:0; transform:translate(0,0); }
      3%     { opacity:.95; }
      22%    { opacity:0; transform:translate(-155px,62px); }
      23%,100%{ opacity:0; transform:translate(0,0); }
    }
    @keyframes bl { 0%,87%,100%{opacity:var(--o,.8)} 90%{opacity:.04} }
    @keyframes beacon { 0%,100%{opacity:.8;r:3} 50%{opacity:.15;r:2.5} }
    @keyframes neon { 0%,100%{opacity:.85} 45%,55%{opacity:.5} }
    .guy   { animation: walk 18s linear infinite; }
    .fa    { animation: fa .45s steps(1) infinite; }
    .fb    { animation: fb .45s steps(1) infinite; }
    .star  { animation: tw var(--d,3s) ease-in-out var(--dl,0s) infinite; }
    .shoot { animation: shoot 11s linear 1.5s infinite; }
    .bl    { animation: bl var(--bd,5s) ease-in-out var(--bdl,0s) infinite; }
    .neon  { animation: neon 2.4s ease-in-out infinite; }
  </style>

  <!-- SKY -->
  <rect width="900" height="200" fill="url(#sky)"/>

  <!-- STARS bright -->
  <circle cx="28"  cy="14" r="1.5" fill="#fff" class="star" style="--d:2.8s;--dl:0s;--o:.9"/>
  <circle cx="88"  cy="8"  r="1.3" fill="#fff" class="star" style="--d:3.5s;--dl:.5s;--o:.85"/>
  <circle cx="152" cy="19" r="1.2" fill="#eef" class="star" style="--d:4.2s;--dl:1.2s;--o:.8"/>
  <circle cx="215" cy="11" r="1.5" fill="#fff" class="star" style="--d:2.4s;--dl:.8s;--o:.9"/>
  <circle cx="278" cy="23" r="1.2" fill="#fff" class="star" style="--d:5.1s;--dl:.3s;--o:.75"/>
  <circle cx="342" cy="9"  r="1.4" fill="#eef" class="star" style="--d:3.8s;--dl:2.0s;--o:.85"/>
  <circle cx="402" cy="16" r="1.5" fill="#fff" class="star" style="--d:2.2s;--dl:.7s;--o:.9"/>
  <circle cx="460" cy="7"  r="1.2" fill="#fff" class="star" style="--d:4.7s;--dl:2.3s;--o:.8"/>
  <circle cx="518" cy="21" r="1.3" fill="#eef" class="star" style="--d:3.1s;--dl:.4s;--o:.82"/>
  <circle cx="572" cy="13" r="1.5" fill="#fff" class="star" style="--d:2.7s;--dl:1.6s;--o:.9"/>
  <circle cx="628" cy="25" r="1.2" fill="#fff" class="star" style="--d:5.4s;--dl:.6s;--o:.7"/>
  <circle cx="684" cy="11" r="1.3" fill="#eef" class="star" style="--d:3.4s;--dl:2.5s;--o:.8"/>
  <circle cx="738" cy="17" r="1.5" fill="#fff" class="star" style="--d:3.0s;--dl:1.0s;--o:.9"/>
  <circle cx="828" cy="8"  r="1.4" fill="#fff" class="star" style="--d:3.9s;--dl:1.5s;--o:.85"/>
  <circle cx="876" cy="21" r="1.2" fill="#eef" class="star" style="--d:4.5s;--dl:.2s;--o:.75"/>
  <!-- STARS dim -->
  <circle cx="60"  cy="31" r=".9" fill="#ccf" class="star" style="--d:6.3s;--dl:.7s;--o:.55"/>
  <circle cx="126" cy="43" r=".8" fill="#aac" class="star" style="--d:7.2s;--dl:1.4s;--o:.5"/>
  <circle cx="190" cy="35" r=".9" fill="#ccf" class="star" style="--d:5.7s;--dl:2.7s;--o:.55"/>
  <circle cx="256" cy="49" r=".8" fill="#aac" class="star" style="--d:6.9s;--dl:.9s;--o:.45"/>
  <circle cx="316" cy="37" r=".9" fill="#aac" class="star" style="--d:7.6s;--dl:2.1s;--o:.5"/>
  <circle cx="374" cy="45" r=".8" fill="#ccf" class="star" style="--d:6.0s;--dl:3.3s;--o:.45"/>
  <circle cx="435" cy="53" r=".9" fill="#aac" class="star" style="--d:6.6s;--dl:.5s;--o:.5"/>
  <circle cx="493" cy="38" r=".8" fill="#ccf" class="star" style="--d:8.1s;--dl:2.9s;--o:.4"/>
  <circle cx="552" cy="47" r=".9" fill="#aac" class="star" style="--d:5.5s;--dl:1.1s;--o:.55"/>
  <circle cx="609" cy="39" r=".8" fill="#ccf" class="star" style="--d:7.4s;--dl:1.0s;--o:.45"/>
  <circle cx="663" cy="53" r=".8" fill="#aac" class="star" style="--d:6.7s;--dl:2.3s;--o:.4"/>
  <circle cx="720" cy="43" r=".9" fill="#ccf" class="star" style="--d:5.8s;--dl:1.6s;--o:.5"/>
  <circle cx="784" cy="31" r=".8" fill="#aac" class="star" style="--d:7.9s;--dl:.8s;--o:.45"/>
  <circle cx="852" cy="46" r=".9" fill="#ccf" class="star" style="--d:6.4s;--dl:1.9s;--o:.5"/>

  <!-- MOON glow -->
  <circle cx="762" cy="44" r="52" fill="#fffff4" opacity="0.045" filter="url(#sg)"/>
  <!-- Moon disk -->
  <circle cx="762" cy="44" r="22" fill="#ffffee"/>
  <!-- Craters -->
  <circle cx="754" cy="38" r="5.5" fill="#e6e6d0" opacity="0.5"/>
  <circle cx="769" cy="50" r="3.5" fill="#e6e6d0" opacity="0.4"/>
  <circle cx="772" cy="36" r="2.5" fill="#e6e6d0" opacity="0.38"/>
  <circle cx="756" cy="51" r="2"   fill="#e6e6d0" opacity="0.32"/>

  <!-- SHOOTING STAR -->
  <g class="shoot">
    <circle cx="622" cy="22" r="2.5" fill="white"/>
    <line x1="636" y1="16" x2="622" y2="22" stroke="white" stroke-width="1.5" stroke-linecap="round" opacity="0.5"/>
  </g>

  <!-- CITY ATMOSPHERIC GLOW -->
  <rect x="420" y="110" width="480" height="60" fill="url(#cg)"/>

  <!-- BUILDINGS - all bottom at y=170 -->
  <rect x="450" y="153" width="38"  height="17" fill="#060b17"/>
  <rect x="492" y="136" width="30"  height="34" fill="#060b17"/>
  <rect x="526" y="126" width="54"  height="44" fill="#07101b"/>
  <rect x="582" y="145" width="30"  height="25" fill="#060b17"/>
  <rect x="616" y="116" width="62"  height="54" fill="#080f1e"/>
  <rect x="682" y="133" width="38"  height="37" fill="#070c18"/>
  <rect x="724" y="112" width="68"  height="58" fill="#090f1f"/>  <!-- tall tower -->
  <rect x="796" y="125" width="46"  height="45" fill="#070c18"/>
  <rect x="845" y="104" width="62"  height="66" fill="#080e1d"/>  <!-- tallest -->
  <!-- Foreground depth buildings -->
  <rect x="462" y="161" width="20"  height="9"  fill="#050a14"/>
  <rect x="596" y="151" width="16"  height="19" fill="#050a14"/>

  <!-- ROOFTOP DETAILS -->
  <!-- Antenna B7 (tall tower) with blinking beacon -->
  <rect x="757" y="100" width="2" height="12" fill="#0c1222"/>
  <circle cx="758" cy="100" r="3" fill="#ff2222">
    <animate attributeName="opacity" values=".8;0.1;.8" dur="1.3s" repeatCount="indefinite"/>
    <animate attributeName="r" values="3;2.5;3" dur="1.3s" repeatCount="indefinite"/>
  </circle>
  <!-- Antenna B9 -->
  <rect x="874" y="91" width="2"  height="13" fill="#0c1222"/>
  <line x1="870" y1="97" x2="879" y2="97" stroke="#0c1222" stroke-width="1.5"/>
  <!-- Water tower B5 -->
  <rect x="635" y="107" width="22" height="9"  rx="1" fill="#070f1c"/>
  <rect x="633" y="105" width="26" height="3"  fill="#060b18"/>
  <!-- Water tower B3 -->
  <rect x="538" y="118" width="16" height="8"  rx="1" fill="#060b17"/>
  <rect x="536" y="116" width="20" height="3"  fill="#060a16"/>

  <!-- NEON SIGN on B7 -->
  <text x="728" y="163" font-family="'Courier New',Courier,monospace" font-size="8"
        fill="#ff79c6" filter="url(#ng)" class="neon">danfry.dev</text>
  <text x="728" y="163" font-family="'Courier New',Courier,monospace" font-size="8"
        fill="#ffb3e8" class="neon">danfry.dev</text>

  <!-- WINDOW LIGHTS B3 -->
  <rect x="533" y="131" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.85;--bd:4.2s;--bdl:.3s"/>
  <rect x="544" y="131" width="5" height="5" rx="1" fill="#bbdefb" style="opacity:.75"/>
  <rect x="556" y="131" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.8;--bd:6.5s;--bdl:2.1s"/>
  <rect x="533" y="143" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.7;--bd:5.8s;--bdl:1.4s"/>
  <rect x="544" y="143" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.82"/>
  <rect x="556" y="143" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.65;--bd:7.1s;--bdl:.8s"/>
  <!-- WINDOW LIGHTS B5 -->
  <rect x="622" y="122" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.9"/>
  <rect x="633" y="122" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.8;--bd:4.8s;--bdl:.2s"/>
  <rect x="647" y="122" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.7;--bd:6.2s;--bdl:2.5s"/>
  <rect x="622" y="134" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.75;--bd:5.3s;--bdl:1.7s"/>
  <rect x="633" y="134" width="5" height="5" rx="1" fill="#bbdefb" style="opacity:.65"/>
  <rect x="647" y="134" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.85;--bd:3.9s;--bdl:.6s"/>
  <rect x="622" y="146" width="5" height="5" rx="1" fill="#bbdefb" style="opacity:.55"/>
  <rect x="647" y="146" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.7;--bd:7.5s;--bdl:3.0s"/>
  <!-- WINDOW LIGHTS B7 tower -->
  <rect x="729" y="118" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.9;--bd:4.4s;--bdl:.1s"/>
  <rect x="740" y="118" width="5" height="5" rx="1" fill="#bbdefb" style="opacity:.8"/>
  <rect x="753" y="118" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.85;--bd:5.7s;--bdl:2.2s"/>
  <rect x="765" y="118" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.65;--bd:6.8s;--bdl:1.0s"/>
  <rect x="729" y="130" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.75;--bd:4.0s;--bdl:2.9s"/>
  <rect x="740" y="130" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.88"/>
  <rect x="753" y="130" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.7;--bd:7.0s;--bdl:.4s"/>
  <rect x="765" y="130" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.9"/>
  <rect x="729" y="142" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.6;--bd:5.2s;--bdl:1.8s"/>
  <rect x="740" y="142" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.75;--bd:4.6s;--bdl:.9s"/>
  <rect x="753" y="142" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.62"/>
  <rect x="765" y="142" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.8;--bd:6.3s;--bdl:2.7s"/>
  <!-- WINDOW LIGHTS B9 -->
  <rect x="849" y="110" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.9;--bd:4.3s;--bdl:.5s"/>
  <rect x="860" y="110" width="5" height="5" rx="1" fill="#bbdefb" style="opacity:.75"/>
  <rect x="871" y="110" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.85;--bd:5.9s;--bdl:1.3s"/>
  <rect x="882" y="110" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.6;--bd:7.8s;--bdl:.7s"/>
  <rect x="849" y="122" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.82"/>
  <rect x="860" y="122" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.85;--bd:4.9s;--bdl:2.4s"/>
  <rect x="871" y="122" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.7;--bd:6.6s;--bdl:.2s"/>
  <rect x="882" y="122" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.68"/>
  <rect x="849" y="134" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.55;--bd:5.1s;--bdl:1.6s"/>
  <rect x="860" y="134" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.8;--bd:3.8s;--bdl:.8s"/>
  <rect x="871" y="134" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.72"/>
  <rect x="882" y="134" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.75;--bd:6.4s;--bdl:2.1s"/>
  <!-- WINDOW LIGHTS B8 -->
  <rect x="800" y="131" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.8;--bd:4.7s;--bdl:1.9s"/>
  <rect x="812" y="131" width="5" height="5" rx="1" fill="#bbdefb" style="opacity:.7"/>
  <rect x="823" y="131" width="5" height="5" rx="1" fill="#fff9c4" class="bl" style="--o:.75;--bd:5.5s;--bdl:.3s"/>
  <rect x="800" y="143" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.9"/>
  <rect x="812" y="143" width="5" height="5" rx="1" fill="#bbdefb" class="bl" style="--o:.65;--bd:7.6s;--bdl:2.4s"/>
  <rect x="823" y="143" width="5" height="5" rx="1" fill="#fff9c4" style="opacity:.82"/>

  <!-- LAMPPOST 1 at x=120 -->
  <rect x="118" y="148" width="3" height="22" fill="#1a2535"/>
  <rect x="118" y="148" width="20" height="3" rx="1" fill="#1a2535"/>
  <rect x="132" y="144" width="9" height="6"  rx="2" fill="#1e2a3c"/>
  <path d="M133 151 L114 170 L158 170 Z" fill="#fff9a0" opacity="0.05"/>
  <circle cx="136" cy="150" r="15" fill="#fff9a0" opacity="0.065" filter="url(#lg)"/>
  <circle cx="136" cy="150" r="3.5" fill="#fff8b0"/>

  <!-- LAMPPOST 2 at x=370 -->
  <rect x="368" y="148" width="3" height="22" fill="#1a2535"/>
  <rect x="368" y="148" width="20" height="3" rx="1" fill="#1a2535"/>
  <rect x="382" y="144" width="9" height="6"  rx="2" fill="#1e2a3c"/>
  <path d="M383 151 L364 170 L408 170 Z" fill="#fff9a0" opacity="0.05"/>
  <circle cx="386" cy="150" r="15" fill="#fff9a0" opacity="0.065" filter="url(#lg)"/>
  <circle cx="386" cy="150" r="3.5" fill="#fff8b0"/>

  <!-- GROUND -->
  <rect x="0" y="170" width="900" height="30" fill="url(#gnd)"/>
  <line x1="0" y1="170" x2="900" y2="170" stroke="#0e1c2e" stroke-width="1"/>
  <!-- City glow on ground -->
  <rect x="420" y="170" width="480" height="8" fill="#ff8800" opacity="0.04"/>

  <!-- ================================================================= -->
  <!-- WALKING PIXEL CHARACTER                                            -->
  <!-- Coords: head top y=128, feet y=170 (ground)                       -->
  <!-- ================================================================= -->
  <g class="guy">

    <!-- Ground shadow -->
    <ellipse cx="8" cy="173" rx="15" ry="3" fill="#000" opacity="0.32"/>

    <!-- FRAME A: legs spread, left arm up, right arm down -->
    <g class="fa">
      <rect x="-5" y="144" width="4" height="13" fill="#FDBCB4"/>  <!-- left arm up   -->
      <rect x="17" y="148" width="4" height="13" fill="#FDBCB4"/>  <!-- right arm down -->
      <rect x="0"  y="158" width="6" height="8"  fill="#1a3a5c"/>  <!-- left leg  -->
      <rect x="10" y="158" width="6" height="8"  fill="#1a3a5c"/>  <!-- right leg -->
      <rect x="-1" y="166" width="8" height="4"  fill="#111"/>     <!-- left shoe -->
      <rect x="9"  y="166" width="8" height="4"  fill="#111"/>     <!-- right shoe -->
    </g>

    <!-- FRAME B: legs closer, right arm up, left arm down -->
    <g class="fb">
      <rect x="-5" y="148" width="4" height="13" fill="#FDBCB4"/>  <!-- left arm down  -->
      <rect x="17" y="144" width="4" height="13" fill="#FDBCB4"/>  <!-- right arm up   -->
      <rect x="3"  y="158" width="6" height="8"  fill="#1a3a5c"/>  <!-- left leg  -->
      <rect x="7"  y="158" width="6" height="8"  fill="#1a3a5c"/>  <!-- right leg -->
      <rect x="2"  y="166" width="8" height="4"  fill="#111"/>     <!-- left shoe -->
      <rect x="6"  y="166" width="8" height="4"  fill="#111"/>     <!-- right shoe -->
    </g>

    <!-- FIXED PARTS (rendered on top) -->
    <!-- Belt/waistband -->
    <rect x="0" y="155" width="16" height="3" fill="#142d47"/>
    <!-- Torso (red jacket) -->
    <rect x="0" y="144" width="16" height="12" fill="#e74c3c"/>
    <!-- Sleeve caps (shirt shoulder over arm) -->
    <rect x="-3" y="144" width="4" height="5" fill="#e74c3c"/>
    <rect x="15" y="144" width="4" height="5" fill="#e74c3c"/>
    <!-- Pocket detail -->
    <rect x="9" y="148" width="4" height="4" fill="#c0392b" opacity="0.65"/>
    <!-- Neck -->
    <rect x="5" y="141" width="6" height="4" fill="#FDBCB4"/>
    <!-- Head -->
    <rect x="1" y="130" width="14" height="12" fill="#FDBCB4" rx="1"/>
    <!-- Hair -->
    <rect x="1" y="128" width="14" height="5" fill="#2c1810"/>
    <!-- Eyes -->
    <rect x="4" y="134" width="3" height="3" fill="#1a1a2e"/>
    <rect x="9" y="134" width="3" height="3" fill="#1a1a2e"/>
    <!-- Eye white highlights -->
    <rect x="5" y="134" width="1" height="1" fill="#fff" opacity=".8"/>
    <rect x="10" y="134" width="1" height="1" fill="#fff" opacity=".8"/>
    <!-- Nose (subtle) -->
    <rect x="7" y="138" width="2" height="1" fill="#c87356" opacity=".38"/>
    <!-- Smile -->
    <rect x="5" y="140" width="6" height="1" fill="#c87356" opacity=".7"/>
    <rect x="5" y="140" width="1" height="2" fill="#c87356" opacity=".45"/>
    <rect x="10" y="140" width="1" height="2" fill="#c87356" opacity=".45"/>
  </g>

</svg>
