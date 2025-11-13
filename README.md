<!-- ตัวการ์ตูน -->
<g transform="translate(140,120)" stroke="#FF0000" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" fill="none">
  <!-- เงา -->
  <ellipse cx="0" cy="30" rx="36" ry="8" fill="#FF0000" opacity="0.12">
    <animate attributeName="rx" values="36;30;36" dur="0.6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.12;0.08;0.12" dur="0.6s" repeatCount="indefinite"/>
  </ellipse>

  <!-- ลำตัว -->
  <line x1="0" y1="-32" x2="0" y2="0"/>
  <path d="M-10 -32 Q0 -40 10 -32"/>

  <!-- หัว + ผม + หน้า -->
  <g transform="translate(0,-44)">
    <circle cx="0" cy="0" r="10"/>
    <path d="M-10 -2 Q0 -8 10 -2"/>
    <circle cx="3" cy="-2" r="1.2" fill="#FF0000"/>
    <path d="M-3 3 Q0 5 3 3"/>
  </g>

  <!-- แขนหลัง -->
  <g transform="translate(0,-28)">
    <g>
      <animateTransform attributeName="transform" type="rotate" values="-35; 10; -35" dur="0.6s" repeatCount="indefinite"/>
      <line x1="0" y1="0" x2="-18" y2="-8"/>
      <line x1="-18" y1="-8" x2="-30" y2="2"/>
    </g>
  </g>

  <!-- แขนหน้า + คอม -->
  <g transform="translate(0,-26)">
    <g>
      <animateTransform attributeName="transform" type="rotate" values="30; -5; 30" dur="0.6s" repeatCount="indefinite"/>
      <line x1="0" y1="0" x2="18" y2="-10"/>
      <g transform="translate(18,-10) rotate(-10)">
        <line x1="0" y1="0" x2="16" y2="-2"/>
        <!-- คอมพิวเตอร์ -->
        <g transform="translate(16,-14)">
          <rect x="0" y="-1" width="28" height="18" rx="2" ry="2" stroke="#FF0000" fill="#050505"/>
          <rect x="1.5" y="0.5" width="25" height="15" fill="#FF0000" opacity="0.14">
            <animate attributeName="opacity" values="0.08;0.18;0.08" dur="1.2s" repeatCount="indefinite"/>
          </rect>
          <g stroke="#FFFFFF" stroke-width="1">
            <line x1="4" y1="4" x2="20" y2="4"/>
            <line x1="4" y1="8" x2="18" y2="8"/>
            <line x1="4" y1="12" x2="22" y2="12"/>
            <animate attributeName="opacity" values="1;0.75;1" dur="0.8s" repeatCount="indefinite"/>
          </g>
          <g transform="translate(0,18)">
            <rect x="-2" y="-1.5" width="32" height="4" rx="1" ry="1"/>
          </g>
        </g>
      </g>
    </g>
  </g>

  <!-- ขาหลัง -->
  <g>
    <animateTransform attributeName="transform" type="rotate" values="30; -25; 30" dur="0.6s" repeatCount="indefinite"/>
    <line x1="0" y1="0" x2="22" y2="12"/>
    <g transform="translate(22,12)">
      <animateTransform attributeName="transform" type="rotate" values="-35; 20; -35" dur="0.6s" repeatCount="indefinite"/>
      <line x1="0" y1="0" x2="18" y2="12"/>
      <path d="M18 12 L28 12"/>
    </g>
  </g>

  <!-- ขาหน้า -->
  <g>
    <animateTransform attributeName="transform" type="rotate" values="-20; 35; -20" dur="0.6s" repeatCount="indefinite"/>
    <line x1="0" y1="0" x2="22" y2="12"/>
    <g transform="translate(22,12)">
      <animateTransform attributeName="transform" type="rotate" values="25; -30; 25" dur="0.6s" repeatCount="indefinite"/>
      <line x1="0" y1="0" x2="18" y2="12"/>
      <path d="M18 12 L28 12"/>
    </g>
  </g>

  <!-- เส้นสปีด -->
  <g stroke="#FF0000" stroke-width="2" opacity="0.8">
    <line x1="-50" y1="-8" x2="-25" y2="-8">
      <animate attributeName="opacity" values="0;1;0" dur="0.9s" repeatCount="indefinite"/>
    </line>
    <line x1="-62" y1="2" x2="-36" y2="2">
      <animate attributeName="opacity" values="0;1;0" dur="0.9s" begin="0.3s" repeatCount="indefinite"/>
    </line>
  </g>
</g>
