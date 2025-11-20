<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>All Starz Technology Limited</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; padding:0; background:#f3f3f3; }
    header { background:#000; color:#fff; padding:20px; text-align:center; }
    nav { background:#111; display:flex; justify-content:center; gap:15px; padding:10px; }
    nav a { color:white; text-decoration:none; font-weight:bold; padding:8px 14px; border-radius:4px; }
    nav a:hover { background:#444; }
    section { padding:30px; background:white; margin:20px auto; width:90%; max-width:900px; border-radius:10px; box-shadow:0 0 8px rgba(0,0,0,0.1); }
    .hidden { display:none; }
    button { padding:10px 18px; border:none; border-radius:5px; background:#007bff; color:white; cursor:pointer; }
    button:hover { background:#005fcc; }
  </style>
</head>
<body>
  <header>
    <h1>All Starz Technology Limited</h1>
    <p>Fast • Reliable • Professional Tech Services</p>
  </header>  <nav>
    <a onclick="openPage('home')">Home</a>
    <a onclick="openPage('about')">About</a>
    <a onclick="openPage('services')">Services</a>
    <a onclick="openPage('gallery')">Gallery</a>
    <a onclick="openPage('contact')">Contact</a>
    <a onclick="openPage('business')">Business Info</a>
  </nav>  <section id="home">
    <h2>Welcome</h2>
    <p>Your hub for websites, app development, device repairs, digital solutions and more.</p>
    <button onclick="openPage('services')">Explore Services</button>
  </section>  <section id="about" class="hidden">
    <h2>About Us</h2>
    <p>All Starz Technology Limited provides high-quality digital solutions for modern businesses and individuals.</p>
    <p>We specialise in web development, device repairs, app creation and technology innovation.</p>
  </section>  <section id="services" class="hidden">
    <h2>Services</h2>
    <ul>
      <li>Website Development (HTML, JS, APIs)</li>
      <li>Mobile App Development</li>
      <li>Phone, Tablet & Laptop Repairs</li>
      <li>AI Automation Tools</li>
      <li>Remote Digital Product Testing</li>
      <li>Technical Support & Consultancy</li>
    </ul>
  </section>  <section id="gallery" class="hidden">
    <h2>Gallery</h2>
    <p>Upload images of devices, repairs, projects, app screenshots or website previews here.</p>
    <button onclick="alert('Gallery system coming soon!')">Upload</button>
  </section>  <section id="contact" class="hidden">
    <h2>Contact</h2>
    <p>Email: support@allstarztech.co.uk</p>
    <p>Phone: 07XXXXXXXXX</p>
    <button onclick="alert('Contact form coming soon!')">Message Us</button>
  </section>  <section id="business" class="hidden">
    <h2>Business Information</h2>
    <p><strong>Company:</strong> All Starz Technology Limited</p>
    <p><strong>Founded:</strong> 2025</p>
    <p><strong>Type:</strong> Tech & Digital Solutions</p>
    <p><strong>Mission:</strong> Deliver technology solutions that are fast, smart and reliable.</p>
  </section>  <script>
    function openPage(page) {
      document.querySelectorAll('section').forEach(s => s.classList.add('hidden'));
      document.getElementById(page).classList.remove('hidden');
    }
  </script></body>
</html>
