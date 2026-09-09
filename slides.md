---
theme: default
background: '#022760'
class: text-white
highlighter: shiki
lineNumbers: false
info: |
  ## From Disrupting to Driving
  Reimagining Student Engagement as a Continuum of Learning Behaviors.
  SSUSD Education Services — professional learning session for upper-secondary faculty.
drawings:
  persist: false
title: From Disrupting to Driving
mdc: true
---

<img src="/ssusd_title_bg.png" class="absolute inset-0 w-full h-full object-cover" />

<div class="absolute" style="top: 66%; left: 5%; right: 5%;">
  <p class="tracking-widest text-xs font-bold" style="color: var(--sky);">PROFESSIONAL LEARNING SESSION</p>
  <h1 class="font-head font-bold mt-1" style="color: white; white-space: nowrap; font-size: 1.9rem; line-height: 1.25;">From Disrupting to Driving</h1>
  <p class="text-sm italic mt-1" style="color: #CFE0EB; max-width: 40rem;">Reimagining Student Engagement as a Continuum of Learning Behaviors</p>
  <p class="text-xs mt-1" style="color: #B9CEE0;">Education Services &nbsp;|&nbsp; Upper Secondary Faculty &nbsp;|&nbsp; Academic Reading & Writing Program</p>
</div>

<!--
Welcome, everyone. Today we're looking at a framework from Dr Amy Berry called the continuum of student engagement, along with some very direct student voice research she conducted with Dr Kellie Picker through ACER. You've all been teaching for years, so you already recognize engagement and disengagement when you see them. What this session offers isn't a new discovery -- it's a shared, precise vocabulary for something we all navigate daily, plus what over a hundred and fifty students told researchers about it in their own words.
-->

---
layout: default
background: white
class: text-black
---

<div class="w-full" style="height: 1.15in; background: var(--navy); margin: -2.5rem -3.5rem 0 -3.5rem; width: calc(100% + 7rem); padding: 0.6rem 3.5rem 0 3.5rem; box-sizing: border-box;">
  <h1 class="font-head text-2xl font-bold" style="color: white;">WHY THIS MATTERS — EVEN AFTER YEARS IN THE CLASSROOM</h1>
</div>
<div class="w-full" style="height: 0.09in; background: var(--sky); margin: 0 -3.5rem; width: calc(100% + 7rem);"></div>

<div class="mt-6">
<p class="italic text-sm" style="color: var(--muted); max-width: 50rem;">You already know engagement when you see it. This session gives us shared, precise language for it — and shows what 158 students told researchers about it directly.</p>

<div class="grid grid-cols-3 gap-4 mt-5">
  <div v-for="it in [
    { icon: 'Compass', title: 'A sharper vocabulary', body: 'Dr Amy Berry\'s six-part continuum of engagement, built from teacher interviews — not another binary of on task / off task.', color: 'var(--navy)' },
    { icon: 'Users', title: 'Direct student voice', body: 'What 158 students, Prep to Year 12, told ACER researchers about what helps them engage — and what shuts them down.', color: 'var(--navy2)' },
    { icon: 'Lightbulb', title: 'Classroom application', body: 'How to use this framework for reflection, discussion, and DOK 3–4 tasks in our own upper-secondary courses.', color: 'var(--sky)' },
  ]" :key="it.title" class="rounded-lg p-4" :style="{ background: 'var(--offwhite)', border: `1px solid ${it.color}` }">
    <div class="w-11 h-11 rounded-full flex items-center justify-center mb-2" :style="{ background: it.color }">
      <Icon :name="it.icon" :size="20" color="white" />
    </div>
    <h3 class="font-head text-sm font-bold" style="color: var(--navy);">{{ it.title }}</h3>
    <p class="text-xs mt-1.5 leading-snug">{{ it.body }}</p>
  </div>
</div>
</div>

<div class="mt-6 text-xs" style="color: var(--muted);">From Disrupting to Driving — SSUSD Education Services</div>

<!--
Three things we'll cover today. First, Berry's six-part continuum, which moves past the simple on-task, off-task binary. Second, direct quotes and findings from the ACER focus groups -- 158 students from Prep all the way through Year 12. And third, and most important for our time together, how we can actually use this in our own upper-secondary classrooms, particularly for the kind of DOK 3 and 4 work we're already asking of our dual-credit students.
-->

---
layout: default
background: '#F2F4F6'
class: text-black
---

<div class="w-full" style="height: 1.15in; background: var(--navy); margin: -2.5rem -3.5rem 0 -3.5rem; width: calc(100% + 7rem); padding: 0.6rem 3.5rem 0 3.5rem; box-sizing: border-box;">
  <h1 class="font-head text-2xl font-bold" style="color: white;">THE RESEARCH BEHIND THE FRAMEWORK</h1>
</div>
<div class="w-full" style="height: 0.09in; background: var(--tan); margin: 0 -3.5rem; width: calc(100% + 7rem);"></div>

<div class="grid grid-cols-2 gap-5 mt-5">
  <div class="rounded-lg p-5" style="background: white; border: 1px solid var(--navy); box-shadow: 0 3px 10px rgba(0,0,0,.08);">
    <div class="w-12 h-12 rounded-full flex items-center justify-center mb-3" style="background: var(--navy);">
      <Icon name="Microscope" :size="22" color="white" />
    </div>
    <h3 class="font-head text-lg font-bold" style="color: var(--navy);">Dr Amy Berry</h3>
    <p class="italic text-xs" style="color: var(--muted);">Research Fellow, ACER &nbsp;|&nbsp; Honorary Fellow, University of Melbourne</p>
    <p class="text-xs mt-3 leading-snug">20+ years in education as classroom teacher, researcher, and professional learning facilitator.</p>
    <p class="text-xs mt-2 leading-snug">10 years teaching in Queensland, Australia, before moving into research on engagement and teacher professional learning.</p>
    <p class="text-xs mt-2 leading-snug">Has worked with teachers and education systems in the U.S., Saudi Arabia, Singapore, Indonesia, the Philippines, and Ukraine.</p>
  </div>

  <div class="rounded-lg p-4" style="background: var(--navy);">
    <h3 class="font-head text-sm font-bold" style="color: var(--sky);">HOW IT WAS BUILT</h3>
    <div class="mt-2">
      <p class="font-bold text-xs" style="color: var(--tan);">2016–17</p>
      <p class="text-xs mt-0.5 leading-snug" style="color: #DCE6EF;">In-depth interviews with classroom teachers exploring how they described and recognized student engagement — both everyday and rare, powerful examples.</p>
    </div>
    <div class="mt-2">
      <p class="font-bold text-xs" style="color: var(--tan);">2020</p>
      <p class="text-xs mt-0.5 leading-snug" style="color: #DCE6EF;">Fisher, Frey & Hattie included the continuum in <em>The Distance Learning Playbook</em>, extending it into remote learning.</p>
    </div>
    <div class="mt-2">
      <p class="font-bold text-xs" style="color: var(--tan);">2024–25</p>
      <p class="text-xs mt-0.5 leading-snug" style="color: #DCE6EF;">Berry and Dr Kellie Picker ran ACER focus groups with 158 students, Prep to Year 12, asking students directly about their own engagement.</p>
    </div>
  </div>
</div>

<div class="mt-4 text-xs" style="color: var(--muted);">From Disrupting to Driving — SSUSD Education Services</div>

<!--
A quick word on where this comes from. Amy Berry isn't a theorist working from a desk -- she taught for a decade in Queensland before moving into research, and she built this continuum from real interviews with classroom teachers describing what engagement and disengagement actually looked like for them. The framework gained wider traction when Fisher, Frey and Hattie folded it into The Distance Learning Playbook during the pandemic. And more recently, Berry teamed up with Dr Kellie Picker to flip the lens -- instead of asking teachers about students, they asked students directly. That's the research we'll spend the second half of this session on.
-->

---
layout: default
background: white
class: text-black
---

<div class="w-full" style="height: 1.05in; background: var(--navy); margin: -2.5rem -3.5rem 0 -3.5rem; width: calc(100% + 7rem); padding: 0.5rem 3.5rem 0 3.5rem; box-sizing: border-box;">
  <h1 class="font-head text-xl font-bold" style="color: white;">A NEW VOCABULARY: THE ENGAGEMENT CONTINUUM</h1>
</div>
<div class="w-full" style="height: 0.09in; background: var(--sky); margin: 0 -3.5rem; width: calc(100% + 7rem);"></div>

<p class="italic text-sm mt-3" style="color: var(--muted);">Six forms of engagement — not a simple on/off switch</p>

<div class="grid grid-cols-6 gap-3 mt-5">
  <div v-for="s in [
    { icon: 'Zap', label: 'Disrupting', sub: 'actively resisting', color: 'var(--gray)' },
    { icon: 'DoorOpen', label: 'Avoiding', sub: 'off task, escaping', color: 'var(--gray)' },
    { icon: 'EyeOff', label: 'Withdrawing', sub: 'flying under radar', color: 'var(--gray)' },
    { icon: 'CheckSquare', label: 'Participating', sub: 'compliant, on task', color: 'var(--navy2)' },
    { icon: 'Search', label: 'Investing', sub: 'curious, questioning', color: 'var(--navy2)' },
    { icon: 'Target', label: 'Driving', sub: 'self-directed goals', color: 'var(--sky)' },
  ]" :key="s.label" class="rounded-lg p-3 text-center" :style="{ background: 'var(--offwhite)', border: `1.5px solid ${s.color}` }">
    <div class="w-12 h-12 mx-auto rounded-full flex items-center justify-center mb-2" :style="{ background: s.color }">
      <Icon :name="s.icon" :size="20" color="white" />
    </div>
    <p class="font-head font-bold text-xs" style="color: var(--navy);">{{ s.label }}</p>
    <p class="text-xs italic mt-1 leading-snug" style="color: var(--muted);">{{ s.sub }}</p>
  </div>
</div>

<div class="flex justify-between text-xs font-bold mt-4">
  <span style="color: var(--gray);">◀ DISENGAGING FROM LEARNING</span>
  <span style="color: var(--navy2);">ENGAGING IN LEARNING ▶</span>
</div>

<p class="text-xs italic mt-3" style="color: var(--muted);">Original continuum diagram concept: Berry (2023, 2022). Recreated for instructional use.</p>

<!--
Here's the full continuum. Six forms of engagement, three on the disengaging side -- Disrupting, Avoiding, Withdrawing -- and three on the engaging side -- Participating, Investing, Driving. Notice this isn't a simple line from bad to good. Berry organized it this way because of how students actually behave, which we'll unpack on the next two slides. For now, just take in the six labels and the two directions -- disengaging from learning on the left, engaging in learning on the right. This diagram is my own recreation of Berry's concept for our purposes today, not a reproduction of her copyrighted book figure.
-->

---
layout: default
---

<div class="absolute inset-0" style="background: #022760; z-index: -1;"></div>
<div class="text-white">

<h1 class="font-head text-3xl font-bold">THREE FORMS OF DISENGAGING</h1>
<p class="italic mt-2 text-sm" style="color: #9FB6CC;">Passive withdrawal → active avoidance → active disruption</p>

<div class="mt-5 space-y-3">
  <div v-for="r in [
    { icon: 'EyeOff', title: 'Withdrawing', body: 'Passive disengagement — \'flying under the radar.\' Distracted, avoiding eye contact, daydreaming, staring out the window. Easy to miss because it causes no disruption.' },
    { icon: 'DoorOpen', title: 'Avoiding', body: 'Actively seeking to escape the task without hiding it: wandering the room, asking to leave, being unprepared, drifting toward off-task peers.' },
    { icon: 'Zap', title: 'Disrupting', body: 'Actively resisting or derailing the lesson: arguing, distracting others, refusing to participate. Reprimands can unintentionally reward this role.' },
  ]" :key="r.title" class="rounded-lg p-3 flex items-center gap-4" style="background: #0B3663;">
    <div class="w-12 h-12 flex-shrink-0 rounded-full flex items-center justify-center" style="background: var(--gray);">
      <Icon :name="r.icon" :size="22" color="white" />
    </div>
    <div>
      <h3 class="font-head text-base font-bold" style="color: var(--sky);">{{ r.title }}</h3>
      <p class="text-xs mt-0.5 leading-snug" style="color: #DCE6EF;">{{ r.body }}</p>
    </div>
  </div>
</div>

<div class="absolute bottom-4 left-8 text-xs" style="color: #9FB6CC;">From Disrupting to Driving — SSUSD Education Services</div>

</div>

<!--
Let's start with the disengaging side. Withdrawing is the one I want us to sit with -- it's the student who has quietly checked out, isn't causing any problems, and can go entire class periods without us noticing anything is wrong. Avoiding is more visible -- the constant bathroom passes, the forgotten materials. And Disrupting is what we're most trained to respond to, because it's loud and it interrupts the room. Berry's research point here is important: our attention naturally goes to Disrupting because it demands it, but Withdrawing does just as much damage to learning -- it's just silent.
-->

---
layout: default
background: white
class: text-black
---

<h1 class="font-head text-3xl font-bold" style="color: var(--navy);">THREE FORMS OF ENGAGING</h1>
<p class="italic mt-2 text-sm" style="color: var(--muted);">Compliant participation → genuine investment → self-directed driving</p>

<div class="mt-5 space-y-3">
  <div v-for="r in [
    { icon: 'CheckSquare', title: 'Participating', body: 'Compliant and on task: listening, doing assigned work, following directions. Necessary — but the most passive form of engagement.', color: 'var(--navy2)' },
    { icon: 'Search', title: 'Investing', body: 'Genuine curiosity and interest: asking questions, joining discussion, thinking more deeply, wanting to share ideas with peers.', color: 'var(--navy2)' },
    { icon: 'Target', title: 'Driving', body: 'The most active form: students set their own learning goals, self-assess, seek feedback, and extend their learning — hallmarks of self-regulated learning.', color: 'var(--sky)' },
  ]" :key="r.title" class="rounded-lg p-3 flex items-center gap-4" style="background: var(--offwhite); box-shadow: 0 2px 8px rgba(0,0,0,.06);">
    <div class="w-12 h-12 flex-shrink-0 rounded-full flex items-center justify-center" :style="{ background: r.color }">
      <Icon :name="r.icon" :size="22" color="white" />
    </div>
    <div>
      <h3 class="font-head text-base font-bold" style="color: var(--navy);">{{ r.title }}</h3>
      <p class="text-xs mt-0.5 leading-snug">{{ r.body }}</p>
    </div>
  </div>
</div>

<div class="mt-4 text-xs" style="color: var(--muted);">From Disrupting to Driving — SSUSD Education Services</div>

<!--
Now the engaging side. Participating is where most classroom management aims -- and to be clear, it's necessary, it's just not sufficient. It's compliance, not investment. Investing is where we start to see real curiosity -- students asking questions because they want to know, not because it's required. And Driving is the top of the continuum: students setting their own goals, self-assessing, seeking out feedback on their own initiative. This maps closely onto self-regulated learning research. For our advanced and dual-credit students especially, Driving should be a realistic target, not an exceptional case.
-->

---
layout: default
---

<div class="absolute inset-0" style="background: #022760; z-index: -1;"></div>
<div class="text-white">

<div class="flex justify-center">
  <div class="w-16 h-16 rounded-full flex items-center justify-center" style="background: var(--sky);">
    <Icon name="ArrowLeftRight" :size="28" color="white" />
  </div>
</div>
<h1 class="font-head text-xl font-bold text-center mt-4">THE KEY INSIGHT FOR VETERAN TEACHERS</h1>

<div class="rounded-lg p-5 mt-5 text-center" style="background: #0B3663; border: 1px solid var(--sky); max-width: 50rem; margin-left: auto; margin-right: auto;">
  <p class="font-head text-lg font-bold" style="color: var(--sky);">The most ACTIVE behaviors sit at BOTH ends of the continuum.</p>
  <p class="mt-3 text-sm" style="color: #DCE6EF;">The most PASSIVE behaviors — Withdrawing and Participating — sit in the middle, not at the "calm" end.</p>
</div>

<div class="mt-5" style="max-width: 50rem; margin-left: auto; margin-right: auto;">
  <p class="font-bold text-sm" style="color: var(--tan);">What this means for our classrooms:</p>
  <ul class="mt-2 space-y-1 text-xs leading-snug" style="color: #DCE6EF;">
    <li>A quiet, compliant student who is simply "participating" is not automatically fully engaged.</li>
    <li>A withdrawing student is often overlooked precisely because they cause no disruption — but the impact on learning is just as serious.</li>
  </ul>
</div>

</div>

<!--
This is the slide I'd ask you to remember above all the others. The most active behaviors -- Driving and Disrupting -- sit at opposite ends. And the most passive behaviors -- Withdrawing and Participating -- sit in the middle, not at some calm, everything's-fine end of the scale. So when we scan a room and see quiet compliance, that's not automatically a green light. It might be full engagement, or it might be a student who has learned exactly how to look engaged without being engaged at all. Worth sitting with for a moment before we move on.
-->

---
layout: default
background: '#F2F4F6'
class: text-black
---

<div class="grid grid-cols-5 gap-0 -m-8 h-full">
  <div class="col-span-2 flex flex-col items-center justify-center p-8" style="background: var(--navy); color: white;">
    <div class="w-24 h-24 rounded-full flex items-center justify-center" style="background: var(--sky);">
      <Icon name="Users" :size="44" color="white" />
    </div>
    <p class="font-head text-6xl font-bold mt-6">158</p>
    <p class="italic text-sm mt-2" style="color: #CFE0EB;">students, Prep to Year 12, in focus groups</p>
  </div>
  <div class="col-span-3 flex flex-col justify-center p-10">
    <h1 class="font-head text-2xl font-bold" style="color: var(--navy);">FROM FRAMEWORK TO STUDENT VOICE</h1>
    <p class="mt-4 text-sm leading-relaxed">Berry's continuum describes engagement from the teacher's vantage point. In a follow-up ACER study, <em>Student Perspectives on Engaging in Learning at School</em>, Berry and Dr Kellie Picker asked students directly.</p>
    <p class="font-bold mt-5 text-sm" style="color: var(--navy);">Two guiding questions from the focus groups:</p>
    <ul class="mt-2 space-y-2 text-sm italic" style="color: var(--navy2);">
      <li>What helps you get more engaged in learning at school?</li>
      <li>What does it feel like when you don't want to engage — and why?</li>
    </ul>
    <p class="text-xs italic mt-8" style="color: var(--muted);">Source: Berry & Picker (2024–2025), Student Perspectives on Engaging in Learning at School, ACER.</p>
  </div>
</div>

<!--
So that's the theoretical framework. Now let's pivot to something I think is even more powerful for our purposes -- actual student voice. In a follow-up study, Berry and Kellie Picker ran focus groups with 158 students spanning Prep all the way through Year 12, and simply asked them what helps and what hinders their own engagement. As experienced teachers, we make a lot of inferences about what's going on for our students. This research is a good reminder that we can just ask them, and that they have a lot to say when we do.
-->

---
layout: default
background: white
class: text-black
---

<h1 class="font-head text-2xl font-bold" style="color: var(--navy);">WHAT STUDENTS TOLD US: 5 TIPS FOR TEACHERS</h1>
<p class="italic mt-2 text-sm" style="color: var(--muted);">Part 1 of the ACER series — "Growing the Seeds of Engagement" (Berry & Picker, 2025)</p>

<div class="grid grid-cols-5 gap-3 mt-8">
  <div v-for="t in [
    { icon: 'Smile', title: '1. Be engaged', body: 'Students read our enthusiasm for the subject — and our lack of it — and it shapes their own motivation.' },
    { icon: 'Lightbulb', title: '2. Be engaging', body: 'We may not choose what we teach, but we choose how. Vary delivery; make content relatable.' },
    { icon: 'Target', title: '3. Help us get actively engaged', body: 'Move students beyond passive compliance: right challenge level, real choice, connection to their lives.' },
    { icon: 'Heart', title: '4. Engage with us', body: 'Relationships matter. Students want to feel known, valued, and believed capable of growth.' },
    { icon: 'Ear', title: '5. Listen to us and trust us', body: 'Voice and choice: ask students about their learning rather than assuming, and hand over real ownership.' },
  ]" :key="t.title" class="rounded-lg p-4 text-center" style="background: var(--offwhite); box-shadow: 0 2px 8px rgba(0,0,0,.06);">
    <div class="w-12 h-12 mx-auto rounded-full flex items-center justify-center mb-3" style="background: var(--tan);">
      <Icon :name="t.icon" :size="22" color="white" />
    </div>
    <p class="font-head font-bold text-sm" style="color: var(--navy);">{{ t.title }}</p>
    <p class="text-xs mt-2 leading-relaxed">{{ t.body }}</p>
  </div>
</div>

<div class="absolute bottom-4 left-8 text-xs" style="color: var(--muted);">From Disrupting to Driving — SSUSD Education Services</div>

<!--
Five tips, straight from students. None of them said they wanted to play games all day, which I think surprises people. What they actually asked for was our own enthusiasm, variety in delivery, real challenge pitched at the right level, genuine relationships, and a say in their own learning. Notice tip three especially -- students explicitly said they want to move past passive participating into investing and driving. They're describing Berry's continuum in their own words, without ever having seen it.
-->

---
layout: default
---

<div class="absolute inset-0" style="background: #022760; z-index: -1;"></div>
<div class="text-white">

<h1 class="font-head text-xl font-bold">INSIDE DISENGAGEMENT: WHAT STUDENTS REPORTED</h1>
<p class="italic mt-2 text-xs" style="color: #9FB6CC;">Part 3 of the ACER series — "Student Voice on Engagement Roadblocks" (Berry & Picker, 2025)</p>

<div class="grid grid-cols-2 gap-4 mt-5">
  <div class="rounded-lg p-4" style="background: #0B3663;">
    <div class="w-11 h-11 rounded-full flex items-center justify-center mb-2" style="background: var(--gray);">
      <Icon name="AlertTriangle" :size="20" color="white" />
    </div>
    <h3 class="font-head text-sm font-bold" style="color: var(--sky);">What disengagement looks like</h3>
    <ul class="mt-2 space-y-1 text-xs leading-snug" style="color: #DCE6EF;">
      <li>Minimizing time on task — bathroom trips, pencil sharpening, "fake reading"</li>
      <li>Talking with friends or distracting peers</li>
      <li>Watching the clock, fiddling, daydreaming</li>
      <li>Letting others carry the group's workload</li>
      <li>Visible frustration — groaning, or in younger students, tears</li>
    </ul>
  </div>
  <div class="rounded-lg p-4" style="background: #0B3663;">
    <div class="w-11 h-11 rounded-full flex items-center justify-center mb-2" style="background: var(--tan);">
      <Icon name="Search" :size="20" color="white" />
    </div>
    <h3 class="font-head text-sm font-bold" style="color: var(--sky);">Root causes students named</h3>
    <ul class="mt-2 space-y-1 text-xs leading-snug" style="color: #DCE6EF;">
      <li>Work that is too easy (bored) or too hard (overwhelmed)</li>
      <li>Feeling anxious about high-stakes moments (assessments, events)</li>
      <li>Repetition of content already mastered, with no challenge added</li>
      <li>Both extremes of teacher control backfire — too little structure, or too little freedom</li>
    </ul>
    <div class="rounded-md p-2 mt-2" style="background: var(--navy2);">
      <p class="text-xs italic leading-snug" style="color: #E4EEF6;">"Asking students what is making it hard is a better option than assuming we know what is going on."</p>
    </div>
  </div>
</div>

<div class="absolute bottom-4 left-8 text-xs" style="color: #9FB6CC;">From Disrupting to Driving — SSUSD Education Services</div>

</div>

<!--
The third study in this series asked students directly about disengagement -- what it feels like, what it looks like in their peers, and why it happens. The behaviors on the left will sound very familiar to anyone who's taught for more than a semester. The root causes on the right are worth lingering on, especially the last one -- students said both an overly loose classroom and an overly controlling one produce the same disengagement. Autonomy and structure aren't opposites we have to choose between; both extremes backfire. The researchers' bottom-line recommendation, in the quote at the bottom, is simple: ask the student, don't assume.
-->

---
layout: default
background: white
class: text-black
---

<h1 class="font-head text-xl font-bold" style="color: var(--navy);">APPLYING THIS IN OUR UPPER-SECONDARY ELA CLASSROOM</h1>
<p class="italic mt-2 text-xs" style="color: var(--muted);">A DOK 3–4 activity idea for dual-credit / advanced courses</p>

<div class="grid grid-cols-2 gap-4 mt-4">
  <div class="rounded-lg p-4" style="background: var(--offwhite); border: 1px solid var(--navy2); box-shadow: 0 2px 8px rgba(0,0,0,.06);">
    <div class="w-11 h-11 rounded-full flex items-center justify-center mb-2" style="background: var(--navy);">
      <Icon name="Pencil" :size="20" color="white" />
    </div>
    <h3 class="font-head text-sm font-bold" style="color: var(--navy);">Student self-location + justification</h3>
    <p class="text-xs mt-2 leading-snug">During a rhetorical analysis or revision task, students identify where they landed on the continuum and cite evidence from their own process.</p>
    <p class="text-xs mt-2 italic leading-snug">Prompt: "Were you participating, investing, or driving during this task? Justify your placement with two specific behaviors, then name one action that would move you one step further."</p>
  </div>
  <div class="rounded-lg p-4" style="background: var(--offwhite); border: 1px solid var(--tan); box-shadow: 0 2px 8px rgba(0,0,0,.06);">
    <div class="w-11 h-11 rounded-full flex items-center justify-center mb-2" style="background: var(--tan);">
      <Icon name="ClipboardList" :size="20" color="white" />
    </div>
    <h3 class="font-head text-sm font-bold" style="color: var(--navy);">Teacher audit of assignment design</h3>
    <ul class="mt-2 space-y-1 text-xs leading-snug">
      <li>Pull a current unit assignment and ask: does this only require Participating, or does it invite Investing and Driving?</li>
      <li>Where could we build in real choice, self-assessment, or peer feedback — the markers of "Driving"?</li>
      <li>Which quiet, compliant students in our rosters might actually be Withdrawing rather than fully engaged?</li>
    </ul>
  </div>
</div>

<div class="absolute bottom-4 left-8 text-xs" style="color: var(--muted);">From Disrupting to Driving — SSUSD Education Services</div>

<!--
Here's where this becomes usable Monday morning. On the left, a DOK 3-4 self-location task: students identify where they landed on the continuum during a task and justify it with specific evidence from their own process, then name one concrete next step. That is metacognition plus rhetorical justification, which fits squarely into the kind of rhetorical analysis and revision work we already assign. On the right, the same exercise turned on ourselves: auditing an assignment to see whether it actually requires anything beyond participating, and being honest about which quiet students might be withdrawing rather than engaged.
-->

---
layout: default
background: white
---

<img src="/ssusd_quote_bg.png" class="absolute inset-0 w-full h-full object-cover" />

<div class="absolute inset-0 p-10 flex flex-col">
  <h1 class="font-head text-2xl font-bold text-white text-right">FACULTY DISCUSSION</h1>

  <div class="flex-1 flex flex-col justify-center space-y-4" style="max-width: 54rem; margin-left: auto; margin-right: auto; width: 100%;">
    <div v-for="(q, i) in [
      'Think of a lesson that wasn\'t inherently fun for students. How did you try to move them toward Investing or Driving?',
      'How do you currently ask students about their own engagement, rather than assuming you already know?',
      'Where in your gradebook or seating chart might a quietly \'Participating\' student actually be Withdrawing?',
    ]" :key="i" class="rounded-lg p-4 flex items-center gap-5" style="background: white;">
      <p class="font-head text-3xl font-bold flex-shrink-0" style="color: var(--navy2); width: 2.5rem;">{{ i + 1 }}</p>
      <p class="text-sm" style="color: var(--ink);">{{ q }}</p>
    </div>
  </div>
</div>

<!--
Three prompts for us to talk through as a faculty. Take a few minutes with an elbow partner on whichever one resonates most. The first asks us to reflect on how we handle content that is not inherently exciting. The second pushes on practice -- do we actually ask students, or do we assume? And the third is the uncomfortable one: which of our currently well-behaved students might actually be withdrawing rather than truly engaged. No need to report out on all three, but let us hear from a few tables.
-->

---
layout: default
background: white
class: text-black
---

<h1 class="font-head text-4xl font-bold" style="color: var(--navy);">KEY TAKEAWAYS</h1>

<div class="grid grid-cols-3 gap-6 mt-10">
  <div class="rounded-lg p-6" style="background: var(--offwhite); box-shadow: 0 3px 10px rgba(0,0,0,.08);">
    <div class="w-14 h-14 rounded-full flex items-center justify-center mb-4" style="background: var(--navy);">
      <Icon name="ArrowLeftRight" :size="26" color="white" />
    </div>
    <h3 class="font-head text-lg font-bold" style="color: var(--navy);">Engagement is a continuum, not a switch</h3>
    <p class="text-sm mt-3">Six distinct forms, from Disrupting to Driving — giving us a shared vocabulary for what we're already seeing.</p>
  </div>
  <div class="rounded-lg p-6" style="background: var(--offwhite); box-shadow: 0 3px 10px rgba(0,0,0,.08);">
    <div class="w-14 h-14 rounded-full flex items-center justify-center mb-4" style="background: var(--sky);">
      <Icon name="CheckCircle" :size="26" color="white" />
    </div>
    <h3 class="font-head text-lg font-bold" style="color: var(--navy);">Active behavior lives at both ends</h3>
    <p class="text-sm mt-3">Passive Withdrawing deserves the same attention as active Disrupting — it's just quieter.</p>
  </div>
  <div class="rounded-lg p-6" style="background: var(--offwhite); box-shadow: 0 3px 10px rgba(0,0,0,.08);">
    <div class="w-14 h-14 rounded-full flex items-center justify-center mb-4" style="background: var(--tan);">
      <Icon name="Ear" :size="26" color="white" />
    </div>
    <h3 class="font-head text-lg font-bold" style="color: var(--navy);">Ask students, don't just assume</h3>
    <p class="text-sm mt-3">Both ACER studies point to the same practice: ask directly what helps or hinders engagement.</p>
  </div>
</div>

<div class="absolute bottom-4 left-8 text-xs" style="color: var(--muted);">From Disrupting to Driving — SSUSD Education Services</div>

<!--
To close, three takeaways. Engagement is not a single switch, it is a continuum with six distinct forms, and having language for each one helps us respond more precisely than just get back on task. Second, active behavior sits at both ends -- do not mistake quiet compliance for full engagement, and do not assume a withdrawing student is fine just because they are not causing trouble. And third, both ACER studies point to the same practical move: ask students directly what is helping or hindering their engagement, rather than assuming we already know. Thank you all for your attention today.
-->

---
layout: default
background: '#F2F4F6'
class: text-black
---

<div class="w-full" style="height: 1.05in; background: var(--navy); margin: -2.5rem -3.5rem 0 -3.5rem; width: calc(100% + 7rem); padding: 0.5rem 3.5rem 0 3.5rem; box-sizing: border-box;">
  <h1 class="font-head text-2xl font-bold" style="color: white;">REFERENCES</h1>
</div>
<div class="w-full" style="height: 0.09in; background: var(--tan); margin: 0 -3.5rem; width: calc(100% + 7rem);"></div>

<p class="italic text-sm mt-3" style="color: var(--muted);">APA 7th edition</p>

<div class="space-y-4 text-xs mt-4" style="max-width: 56rem;">
  <p style="padding-left: 2rem; text-indent: -2rem;">Berry, A. (2023, July 4). Reimagining student engagement as a continuum of learning behaviors. <em>MindShift, KQED</em>. https://www.kqed.org/mindshift/61926/reimagining-student-engagement-as-a-continuum-of-learning-behaviors</p>
  <p style="padding-left: 2rem; text-indent: -2rem;">Berry, A., & Picker, K. (2025, February 10). Growing the seeds of engagement: Students share their top tips for teachers. <em>Teacher Magazine</em>, Australian Council for Educational Research. https://www.teachermagazine.com/au_en/articles/growing-the-seeds-of-engagement-students-share-their-top-tips-for-teachers</p>
  <p style="padding-left: 2rem; text-indent: -2rem;">Berry, A., & Picker, K. (2025, March 12). Student voice on engagement roadblocks in learning at school. <em>Teacher Magazine</em>, Australian Council for Educational Research. https://www.teachermagazine.com/au_en/articles/student-voice-on-engagement-roadblocks-in-learning-at-school</p>
  <p style="padding-left: 2rem; text-indent: -2rem;">Fisher, D., Frey, N., & Hattie, J. (2020). <em>The distance learning playbook: Teaching for engagement and impact in any setting</em>. Corwin.</p>
</div>

<div class="flex items-end justify-between mt-4">
  <p class="text-xs italic" style="color: var(--muted);">Icons: Lucide (ISC License), lucide.dev — open-source icon library, used under license.</p>
  <img src="/ssusd_logo.png" style="width: 1.7in;" />
</div>

<!--
Full references for everything cited today, in APA seventh edition format, since that is the convention in education and teaching literature -- the KQED excerpt from Berry's book, and both Teacher Magazine articles from the ACER series. Icon attribution is included as well. This slide is for reference and is not read aloud.
-->
