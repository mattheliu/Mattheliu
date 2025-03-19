## Hi there 👋

<div align="center">
  <!-- CRT屏幕效果容器 -->
  <div style="
    position:relative;
    padding:2rem;
    background:#001100;
    border:3px solid #20C20E;
    box-shadow:0 0 30px #20C20E33,
              inset 0 0 30px #20C20E33;
    font-family:'Courier New',monospace;
    color:#20C20E;
    text-shadow:0 0 5px #20C20E;
  ">
    <!-- 扫描线效果 -->
    <div style="
      position:absolute;
      top:0;left:0;right:0;bottom:0;
      background:repeating-linear-gradient(
        0deg,
        #00000000 0px,
        #00000022 3px,
        #00000044 4px
      );
      pointer-events:none;
      animation:scan 8s linear infinite;
    "></div>


<!-- Glitch文本效果 -->

<h1 style="
  position:relative;
  margin:0;
  font-size:3rem;
  animation:glitch 2s infinite steps(1);
">
  <span aria-hidden>mattheliu@root:~#</span>
  █▀▀▀▀▀█ ▄▀ ▀▄█ █▀▀▀▀▀█
  █ ███ █ ▀█▀██▀ █ ███ █
  █ ▀▀▀ █ ▄▀▄ ▀▄ █ ▀▀▀ █
  ▀▀▀▀▀▀▀ █▄▀ ▀ █ ▀▀▀▀▀▀▀
  ▄ ▄▄ ▀▄▀▀▄█▄▀▀ ▀ ▄█ ▄▄ 
  ▄▀▀▄▀█▄▄▀▀▀▀▀██▀▀▀▄▀▄▀▀
  ▀▀▀ ▀ ▄▄▀█▀▀▀ ▀▀██ █▄▀▄
  █▀▀▀▀▀█ █▄▀▀ █▀█ █ █ ▄▀
  █ ███ █ █ ▀█▄█▀▀▀▀▀▀ ▀ 
  █ ▀▀▀ █ █▀▄▀▀▀ ▄▀▀ ▄▀▀▄
  ▀▀▀▀▀▀▀ ▀▀  ▀▀▀▀ ▀▀▀ ▀▀
</h1>

<!-- 动态终端模拟 -->

<pre style="
  border-top:1px solid #20C20E55;
  padding-top:1rem;
  overflow:hidden;
  white-space:pre-wrap;
  animation:typing 20s steps(100) infinite;
">

[<span style="color:#20C20E">✔</span>] Compiling neural matrix...
[<span style="color:#20C20E">▲</span>] Booting quantum kernel
[<span style="color:#20C20E">⟳</span>] Decrypting shadow protocols
<span style="opacity:0.7">>> Access level: <blink style="animation:blink 1s infinite">DARKNET_ROOT</blink></span>
</pre>

</div>

<!-- 三维ASCII分隔线 -->

<div style="
    font-size:0.7rem;
    color:#20C20E;
    margin:2rem 0;
    transform:rotateX(60deg) rotateZ(-2deg);
    display:inline-block;
  ">
    ░▒▓⎽⎽⎽⎽⎽⎽⎽⎽⎽[ <span style="color:#A0F0A0">terminal_interface</span> ]⎽⎽⎽⎽⎽⎽⎽⎽⎽▓▒░
  </div>
</div>

<style>
  @keyframes scan {
    from { background-position:0 100%; }
    to { background-position:0 0; }
  }

  @keyframes glitch {
    0% { text-shadow:3px 0 #FF00FF,-3px 0 #00FFFF; }
    33% { clip-path:inset(10% 0 30% 0); }
    66% { clip-path:inset(40% 0 10% 0); }
    100% { text-shadow:none; clip-path:none; }
  }

  @keyframes typing {
    from { height:0; }
    10% { height:auto; }
    90% { height:auto; }
    to { height:0; }
  }

  @keyframes blink {
    50% { opacity:0; }
  }
</style>
