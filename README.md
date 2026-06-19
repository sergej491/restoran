# restoran!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Scotty's Hometown Grill — Elevated Comfort Food, Taylorsville NC</title>
<meta name="description" content="Family-owned American grill in Taylorsville, NC. Southern breakfast, hand-cut steaks, burgers, wings and homemade pies." />
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;1,400&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
<script src="https://cdn.tailwindcss.com"></script>
<script>
tailwind.config = { theme: { extend: {
  fontFamily: { display:['"Playfair Display"','serif'], sans:['Inter','sans-serif'] },
  colors: { burgundy:'#5b1a1f', cream:'#f6efe2', gold:'#c79a4a', goldsoft:'#e2c07a', ink:'#1b1411' },
  boxShadow: { elegant:'0 30px 80px -20px rgba(0,0,0,.35)' },
}}}
</script>
<style>
  html { scroll-behavior:smooth; }
  body { font-family:'Inter',sans-serif; background:#f6efe2; color:#1b1411; }
  .font-display { font-family:'Playfair Display',serif; }
  @keyframes kenburns { 0%{transform:scale(1)} 100%{transform:scale(1.08)} }
  .animate-kenburns { animation: kenburns 18s ease-in-out infinite alternate; }
  @keyframes fadeup { from{opacity:0;transform:translateY(20px)} to{opacity:1;transform:none} }
  .animate-fade-up { animation: fadeup 1s ease forwards; }
  .hero-grad { background: linear-gradient(to top, rgba(27,20,17,.85) 0%, rgba(27,20,17,.4) 40%, rgba(27,20,17,.15) 70%, rgba(27,20,17,.5) 100%); }
</style>
</head>
<body class="bg-cream text-ink">

<<header class="fixed top-0 inset-x-0 z-50 backdrop-blur-md bg-[rgba(40,20,22,.75)] border-b border-white/10">
  <div class="max-w-7xl mx-auto px-6 h-16 flex items-center justify-between">
    <a href="#top" class="flex items-center gap-2 text-cream">
      <span class="font-display text-xl tracking-wide">Scotty's</span>
      <span class="text-gold text-[10px] tracking-[0.3em] uppercase">Hometown Grill</span>
    </a>
    <nav class="hidden md:flex items-center gap-8 text-sm text-cream/80">
      <a href="#story" class="hover:text-gold">Our Story</a>
      <a href="#menu" class="hover:text-gold">Menu</a>
      <a href="#home" class="hover:text-gold">Our Home</a>
      <a href="#reviews" class="hover:text-gold">Reviews</a>
      <a href="#visit" class="hover:text-gold">Visit</a>
    </nav>
    <a href="#reserve" class="hidden sm:inline-flex px-5 py-2 text-[10px] tracking-[0.2em] uppercase border border-gold text-gold hover:bg-gold hover:text-burgundy transition">Reserve</a>
  </div>
</header>

<section id="top" class="relative h-screen min-h-[680px] overflow-hidden">
  <img src="scottys-restaurant.jpg" alt="Scotty's Hometown Grill exterior" class="absolute inset-0 w-full h-full object-cover animate-kenburns" />
  <div class="absolute inset-0 hero-grad"></div>
  <div class="relative z-10 h-full max-w-7xl mx-auto px-6 flex flex-col justify-end pb-24">
    <div class="max-w-2xl animate-fade-up">
      <p class="text-gold text-xs tracking-[0.4em] uppercase mb-6">Taylorsville · North Carolina</p>
      <h1 class="font-display text-cream text-5xl md:text-7xl lg:text-8xl leading-[0.95]">Comfort food,<span class="italic text-goldsoft"> elevated.</span></h1>
      <p class="mt-6 text-cream/85 text-lg md:text-xl max-w-xl font-light">A family table set since day one — Southern soul on the plate, candlelight in the room, and the kind of welcome that keeps a town coming back.</p>
      <div class="mt-10 flex flex-wrap gap-4">
        <a href="#reserve" class="px-8 py-4 bg-gold text-burgundy text-[11px] tracking-[0.25em] uppercase font-medium hover:bg-cream transition shadow-elegant">Reserve a Table</a>
        <a href="#menu" class="px-8 py-4 border border-cream/40 text-cream text-[11px] tracking-[0.25em] uppercase hover:bg-white/10 transition">Order Online</a>
      </div>
    </div>
  </div>
  <div class="absolute bottom-6 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2 text-cream/70 text-xs tracking-[0.3em] uppercase">
    <span class="text-gold">★</span> 4.4 · 1,765 reviews
  </div>
</section>

<section id="story" class="py-28 md:py-40 bg-cream">
  <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-2 gap-16 items-center">
    <div class="relative">
      <img src="scottys-restaurant.jpg" alt="Scotty's exterior" class="w-full aspect-[4/3] object-cover shadow-elegant" />
      <div class="absolute -bottom-6 -right-6 bg-burgundy text-cream px-8 py-6 hidden md:block">
        <p class="font-display italic text-2xl">Est. a long time ago,</p>
        <p class="text-gold text-xs tracking-[0.3em] uppercase mt-1">still family-run</p>
      </div>
    </div>
    <div>
      <p class="text-burgundy text-xs tracking-[0.4em] uppercase mb-6">Our Story</p>
      <h2 class="font-display text-4xl md:text-5xl leading-tight">A neighborhood table,<span class="italic"> set with care.</span></h2>
      <div class="w-14 h-px bg-gold my-8"></div>
      <p class="text-ink/70 text-lg leading-relaxed mb-6 font-light">Scotty's began as a small-town diner with a simple promise — food made the way grandma made it, served by people who remember your name and your order.</p>
      <p class="text-ink/70 text-lg leading-relaxed font-light">Years later, that promise still holds. The pies are still hand-rolled before sunrise, the steaks are still hand-cut, and the coffee pot is still always on.</p>
      <div class="mt-10 grid grid-cols-3 gap-6 max-w-md">
        <div><p class="font-display text-3xl text-burgundy">1,765</p><p class="text-xs tracking-[0.2em] uppercase text-ink/60 mt-1">Reviews</p></div>
        <div><p class="font-display text-3xl text-burgundy">4.4★</p><p class="text-xs tracking-[0.2em] uppercase text-ink/60 mt-1">Rating</p></div>
        <div><p class="font-display text-3xl text-burgundy">6 AM</p><p class="text-xs tracking-[0.2em] uppercase text-ink/60 mt-1">Doors open</p></div>
      </div>
    </div>
  </div>
</section>

<section id="menu" class="py-28 md:py-40 bg-[#efe7d4]">
  <div class="max-w-7xl mx-auto px-6">
    <div class="text-center mb-20">
      <p class="text-burgundy text-xs tracking-[0.4em] uppercase mb-4">The Menu</p>
      <h2 class="font-display text-4xl md:text-6xl">Signature plates</h2>
      <div class="w-14 h-px bg-gold mx-auto mt-6"></div>
      <p class="mt-6 text-ink/70 max-w-xl mx-auto font-light">From sunrise breakfast to candlelit dinner — every plate is made in-house, every day.</p>
    </div>
    <div id="menu-grid" class="grid md:grid-cols-2 lg:grid-cols-3 gap-6"></div>
    <div class="text-center mt-16">
      <a href="#reserve" class="inline-block px-10 py-4 bg-burgundy text-cream text-[11px] tracking-[0.25em] uppercase hover:bg-black transition">Order Online</a>
    </div>
  </div>
</section>

<section id="home" class="py-28 md:py-40 bg-cream">
  <div class="max-w-7xl mx-auto px-6">
    <div class="text-center mb-16">
      <p class="text-burgundy text-xs tracking-[0.4em] uppercase mb-4">Our Home</p>
      <h2 class="font-display text-4xl md:text-6xl">30 Buffett Blvd</h2>
      <div class="w-14 h-px bg-gold mx-auto mt-6"></div>
      <p class="mt-6 text-ink/70 max-w-xl mx-auto font-light">The same brick building, the same green awnings, the same red doors — welcoming neighbors for generations.</p>
    </div>
    <div class="relative overflow-hidden shadow-elegant">
      <img src="scottys-restaurant.jpg" alt="Restaurant exterior" class="w-full aspect-[16/9] object-cover" />
      <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-burgundy/90 to-transparent p-8 md:p-12">
        <p class="font-display text-cream text-2xl md:text-3xl italic">Come as a stranger, leave as family.</p>
      </div>
    </div>
  </div>
</section>

<section id="reviews" class="py-28 md:py-40 bg-burgundy text-cream">
  <div class="max-w-4xl mx-auto px-6 text-center">
    <p class="text-gold text-xs tracking-[0.4em] uppercase mb-6">Word of Mouth</p>
    <div class="flex justify-center gap-1 mb-10 text-gold text-xl">★★★★★</div>
    <blockquote id="quote" class="font-display italic text-3xl md:text-5xl leading-[1.2] min-h-[180px]"></blockquote>
    <div class="mt-10">
      <p id="qname" class="font-display text-xl text-gold"></p>
      <p id="qsub" class="text-cream/60 text-xs tracking-[0.3em] uppercase mt-2"></p>
    </div>
    <div class="mt-14 flex items-center justify-center gap-6">
      <button onclick="rev(-1)" class="w-12 h-12 rounded-full border border-cream/30 hover:bg-white/10">‹</button>
      <div id="dots" class="flex gap-2"></div>
      <button onclick="rev(1)" class="w-12 h-12 rounded-full border border-cream/30 hover:bg-white/10">›</button>
    </div>
  </div>
</section>

<section class="py-20 bg-[#efe7d4]">
  <div class="max-w-6xl mx-auto px-6 grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-8 text-center text-burgundy">
    <div><p class="text-2xl">👶</p><p class="text-xs tracking-wider uppercase text-ink/70 mt-2">Kids menu</p></div>
    <div><p class="text-2xl">♿</p><p class="text-xs tracking-wider uppercase text-ink/70 mt-2">Accessible</p></div>
    <div><p class="text-2xl">🚗</p><p class="text-xs tracking-wider uppercase text-ink/70 mt-2">Free parking</p></div>
    <div><p class="text-2xl">💳</p><p class="text-xs tracking-wider uppercase text-ink/70 mt-2">Contactless</p></div>
    <div><p class="text-2xl">🌿</p><p class="text-xs tracking-wider uppercase text-ink/70 mt-2">Vegetarian</p></div>
    <div><p class="text-2xl">🍽️</p><p class="text-xs tracking-wider uppercase text-ink/70 mt-2">Dine · Takeout</p></div>
  </div>
</section>

<section id="visit" class="py-28 md:py-40 bg-cream">
  <div class="max-w-7xl mx-auto px-6 grid lg:grid-cols-2 gap-16">
    <div id="reserve">
      <p class="text-burgundy text-xs tracking-[0.4em] uppercase mb-4">Reserve · Order · Visit</p>
      <h2 class="font-display text-4xl md:text-5xl leading-tight">Pull up a chair.<span class="italic block text-burgundy">We saved you one.</span></h2>
      <div class="w-14 h-px bg-gold my-8"></div>
      <div class="space-y-6 mb-10">
        <div><p class="text-xs tracking-[0.3em] uppercase text-gold mb-1">Find us</p><p>30 Buffett Blvd<br/>Taylorsville, NC 28681</p></div>
        <div><p class="text-xs tracking-[0.3em] uppercase text-gold mb-1">Call ahead</p><a href="tel:+18286355635" class="hover:text-burgundy">+1 (828) 635-5635</a></div>
        <div><p class="text-xs tracking-[0.3em] uppercase text-gold mb-1">Hours</p><p>Breakfast · 6 – 11 AM daily<br/>Lunch & Dinner · 11 AM – 10 PM daily</p></div>
      </div>
      <form onsubmit="event.preventDefault();location.href='tel:+18286355635'" class="space-y-4 bg-white p-8 shadow-elegant border border-ink/10">
        <p class="font-display text-2xl mb-2">Request a table</p>
        <div class="grid sm:grid-cols-2 gap-4">
          <input placeholder="Your name" class="w-full bg-transparent border border-ink/15 px-4 py-3 text-sm focus:outline-none focus:border-gold" />
          <input placeholder="Phone" type="tel" class="w-full bg-transparent border border-ink/15 px-4 py-3 text-sm focus:outline-none focus:border-gold" />
          <input placeholder="Date" type="date" class="w-full bg-transparent border border-ink/15 px-4 py-3 text-sm focus:outline-none focus:border-gold" />
          <input placeholder="Guests" type="number" min="1" value="2" class="w-full bg-transparent border border-ink/15 px-4 py-3 text-sm focus:outline-none focus:border-gold" />
        </div>
        <textarea placeholder="Anything we should know? (allergies, occasion…)" rows="3" class="w-full bg-transparent border border-ink/15 px-4 py-3 text-sm focus:outline-none focus:border-gold resize-none"></textarea>
        <button type="submit" class="w-full py-4 bg-burgundy text-cream text-[11px] tracking-[0.25em] uppercase hover:bg-black transition">Reserve My Table</button>
      </form>
    </div>
    <div class="lg:sticky lg:top-28 h-fit">
      <div class="aspect-[4/5] overflow-hidden shadow-elegant">
        <iframe title="Map" src="https://www.google.com/maps?q=30+Buffett+Blvd,+Taylorsville,+NC+28681&output=embed" class="w-full h-full" loading="lazy"></iframe>
      </div>
    </div>
  </div>
</section>

<<footer class="bg-burgundy text-cream pt-20 pb-10">
  <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-3 gap-12">
    <div>
      <p class="font-display text-3xl">Scotty's</p>
      <p class="text-gold text-xs tracking-[0.3em] uppercase mt-1">Hometown Grill</p>
      <p class="mt-6 text-cream/70 text-sm leading-relaxed font-light max-w-sm">Family-owned. Family-loved. Serving Taylorsville with elevated comfort food, three meals a day.</p>
    </div>
    <div>
      <p class="text-gold text-xs tracking-[0.3em] uppercase mb-4">Visit</p>
      <p class="text-cream/80 text-sm leading-relaxed">30 Buffett Blvd<br/>Taylorsville, NC 28681<br/><a href="tel:+18286355635" class="hover:text-gold">+1 (828) 635-5635</a></p>
    </div>
    <div>
      <p class="text-gold text-xs tracking-[0.3em] uppercase mb-4">Follow</p>
      <div class="flex gap-4">
        <a href="#" class="w-10 h-10 border border-cream/30 flex items-center justify-center hover:bg-gold hover:text-burgundy">IG</a>
        <a href="#" class="w-10 h-10 border border-cream/30 flex items-center justify-center hover:bg-gold hover:text-burgundy">FB</a>
      </div>
    </div>
  </div>
  <div class="max-w-7xl mx-auto px-6 mt-16 pt-8 border-t border-cream/10 flex flex-col md:flex-row items-center justify-between gap-4 text-cream/50 text-xs tracking-wider">
    <p>© <span id="yr"></span> Scotty's Hometown Grill. All rights reserved.</p>
    <p class="uppercase">Made with love in Taylorsville, NC</p>
  </div>
</footer>

<script>
document.getElementById('yr').textContent = new Date().getFullYear();

const menu = [
  ['Breakfast & Brunch','Buttermilk pancakes, country eggs, applewood bacon and bottomless coffee — served daily 6–11 AM.','$10–14','☕'],
  ['Hand-Cut Steaks','Aged ribeye, NY strip and sirloin, finished with herb butter and skillet potatoes.','$18–24','🥩'],
  ['The Bacon Cheeseburger','Half-pound smash patty, cave-aged cheddar, thick-cut bacon and golden onion rings.','$14','🍔'],
  ['Triple-Decker Club','Roasted turkey, smoked ham, crisp bacon, garden lettuce and hand-cut fries.','$13','🥪'],
  ['Honey-Buffalo Wings','Crispy double-fried wings tossed in our house honey-buffalo glaze.','$12','🔥'],
  ['Coconut Cream Pie',"Grandma's recipe — silky custard, toasted coconut and fresh whipped cream.",'$7','🥧'],
];
document.getElementById('menu-grid').innerHTML = menu.map(([n,d,p,i])=>`
  <article class="group bg-white border border-ink/10 p-8 hover:shadow-elegant transition duration-500">
    <div class="w-12 h-12 bg-burgundy/5 border border-burgundy/15 flex items-center justify-center mb-6 text-xl">${i}</div>
    <div class="flex items-baseline justify-between gap-4">
      <h3 class="font-display text-2xl">${n}</h3>
      <span class="text-gold font-display text-lg whitespace-nowrap">${p}</span>
    </div>
    <div class="w-8 h-px bg-gold my-4"></div>
    <p class="text-ink/70 text-sm leading-relaxed font-light">${d}</p>
  </article>`).join('');

const testimonials = [
  ["The friendliest staff in Taylorsville and the coconut cream pie is worth the drive on its own. A true neighborhood treasure.","Marjorie L.","Local since '98"],
  ["Generous portions, fresh ingredients, and the kind of warm welcome that's almost impossible to find these days. We come every Sunday.","The Whitaker Family","Regulars"],
  ["Hands down the best breakfast in Alexander County. The biscuits are perfect and the coffee never stops flowing.","Daniel R.","Google review · ★★★★★"],
];
let ti = 0;
function renderRev(){
  const [q,n,s] = testimonials[ti];
  document.getElementById('quote').textContent = '"'+q+'"';
  document.getElementById('qname').textContent = n;
  document.getElementById('qsub').textContent = s;
  document.getElementById('dots').innerHTML = testimonials.map((_,i)=>`<button onclick="ti=${i};renderRev()" class="h-1 transition-all ${i===ti?'w-10 bg-gold':'w-4 bg-white/30'}"></button>`).join('');
}
function rev(d){ ti = (ti+d+testimonials.length)%testimonials.length; renderRev(); }
renderRev();
setInterval(()=>rev(1), 7000);
</script>
</body>
</html>
