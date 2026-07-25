<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<header>
  <img src="2.png" alt="Profile picture" class="profile-pic">
  <h1><a href="https://guns.lol/lunezo79" target="_blank">Lunezo79</a></h1>
  <p>Roblox Studio Developer — Modeler | Builder | UI Designerr</p>
</header>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    background: radial-gradient(circle at center, #2a1a3d 0%, #150d1f 35%, #0a0508 70%, #000000 100%);
    background-attachment: fixed;
    color: #111;
    font-family: 'Segoe UI', Arial, sans-serif;
    min-height: 100vh;
  }

  header {
    text-align: center;
    padding: 60px 20px 40px;
    color: #ffffff;
  }

  header h1 {
    font-size: 2.5rem;
    letter-spacing: 1px;
  }

  header h1 a {
    color: #ffffff;
    text-decoration: none;
  }

  header h1 a:hover {
    text-decoration: underline;
  }

  header p {
    color: #aaaaaa;
    margin-top: 10px;
    font-size: 1.1rem;
  }

  .container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 20px;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 25px;
    margin-bottom: 50px;
  }

  .box {
    background-color: #3b1f52;
    border: 1px solid rgba(255, 255, 255, 0.15);
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.4);
    color: #ffffff;
    transition: transform 0.35s ease, box-shadow 0.35s ease, border-color 0.35s ease;
  }

  .box:hover {
    transform: translateY(-8px) scale(1.03);
    border-color: rgba(255, 255, 255, 0.6);
    box-shadow: 0 0 25px rgba(255, 255, 255, 0.35), 0 15px 30px rgba(0,0,0,0.5);
  }

  .box img {
    width: 100%;
    border-radius: 6px;
    margin-bottom: 15px;
    display: block;
  }

  .box h2 {
    font-size: 1.3rem;
    margin-bottom: 8px;
    color: #ffffff;
  }

  .box p {
    font-size: 0.95rem;
    color: #d9d3e0;
    line-height: 1.4;
  }

  .section-title {
    color: #ffffff;
    font-size: 1.6rem;
    margin: 40px 0 20px;
    border-left: 4px solid #ffffff;
    padding-left: 12px;
  }

  footer {
    text-align: center;
    color: #666666;
    padding: 30px;
    font-size: 0.9rem;
  }
</style>
</head>
<body>

  <div class="container">

    <div class="section-title">Projects</div>
    <div class="grid">

      <div class="box">
        <img src="https://via.placeholder.com/400x220" alt="Project screenshot">
        <h2>Project Name 1</h2>
        <p>Short description of what this project is, what you built, and what tools/systems you used.</p>
      </div>

      <div class="box">
        <img src="https://via.placeholder.com/400x220" alt="Project screenshot">
        <h2>Project Name 2</h2>
        <p>Short description of what this project is, what you built, and what tools/systems you used.</p>
      </div>

      <div class="box">
        <img src="https://via.placeholder.com/400x220" alt="Project screenshot">
        <h2>Project Name 3</h2>
        <p>Short description of what this project is, what you built, and what tools/systems you used.</p>
      </div>

    </div>

    <div class="section-title">Skills</div>
    <div class="grid">

      <div class="box">
        <h2>Scripting</h2>
        <p>Lua, DataStores, RemoteEvents, Module Scripts, etc.</p>
      </div>

      <div class="box">
        <h2>Building</h2>
        <p>Terrain, environment design, lighting, optimization.</p>
      </div>

      <div class="box">
        <h2>UI / UX</h2>
        <p>Custom GUI design, menus, HUDs, animations.</p>
      </div>

    </div>

  </div>

</body>
</html>
