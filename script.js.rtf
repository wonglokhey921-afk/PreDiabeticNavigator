{\rtf1\ansi\ansicpg1252\cocoartf2761
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 // SIMULATED STATE\
let currentScore = 85;\
let mealLog = [];\
\
// Navigation Logic\
function switchScreen(screenId) \{\
    // Hide all screens\
    document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));\
    document.querySelectorAll('.nav-item').forEach(n => n.classList.remove('active'));\
    \
    // Show selected screen\
    document.getElementById(screenId).classList.add('active');\
    \
    // Highlight nav button\
    const navIndex = screenId === 'dashboard' ? 0 : screenId === 'log' ? 1 : 2;\
    document.querySelectorAll('.nav-item')[navIndex].classList.add('active');\
\}\
\
// Meal Type Selection\
function selectType(btn, type) \{\
    document.querySelectorAll('.icon-btn').forEach(b => b.classList.remove('active'));\
    btn.classList.add('active');\
\}\
\
// FEATURE: SIMULATED VOICE INPUT (Refinement 1)\
function simulateVoice() \{\
    const input = document.getElementById('mealInput');\
    const btn = document.getElementById('voiceBtn');\
    \
    // UI Feedback for listening\
    btn.innerHTML = '<i class="fas fa-spinner fa-spin"></i>';\
    \
    setTimeout(() => \{\
        // Simulate text appearing "Just-in-Time"\
        input.value = "Grilled chicken with brown rice and broccoli";\
        btn.innerHTML = '<i class="fas fa-microphone"></i>';\
        alert("Voice detected: 'Grilled chicken with brown rice and broccoli'");\
    \}, 1500);\
\}\
\
// FEATURE: AI & TRAFFIC LIGHT LOGIC (Refinement 2)\
function saveMeal() \{\
    const meal = document.getElementById('mealInput').value;\
    \
    if(!meal) \{\
        alert("Please enter a meal first.");\
        return;\
    \}\
\
    // Simulate AI Analysis\
    // If the meal contains "sugar", "cake", or "soda", trigger a risk warning\
    const unhealthyKeywords = ['sugar', 'cake', 'soda', 'candy', 'fries', 'white rice'];\
    let isRisky = unhealthyKeywords.some(word => meal.toLowerCase().includes(word));\
\
    if(isRisky) \{\
        // Update Dashboard AI Tip\
        document.getElementById('dashboard-ai-tip').innerText = `Warning: High glycemic load detected in recent meal ($\{meal\}). Consider a 10-minute walk now.`;\
        document.getElementById('dashboard-ai-tip').parentElement.style.borderLeft = "5px solid #f44336";\
        \
        // Update Ring\
        currentScore -= 10;\
        updateRing(currentScore);\
\
        // Update Insights Traffic Light to AMBER\
        document.getElementById('trafficLight').className = 'traffic-light amber';\
        document.getElementById('summaryTitle').innerText = "Caution Needed";\
        document.getElementById('summaryDesc').innerText = "Recent spike detected.";\
        document.getElementById('todayBar').style.background = "#ff9800";\
    \} else \{\
        // Positive Reinforcement\
        document.getElementById('dashboard-ai-tip').innerText = `Great choice! $\{meal\} is rich in fiber and helps stabilize glucose.`;\
        document.getElementById('dashboard-ai-tip').parentElement.style.borderLeft = "5px solid #4caf50";\
        \
        // Update Ring\
        currentScore = Math.min(100, currentScore + 5);\
        updateRing(currentScore);\
\
        // Update Insights Traffic Light to GREEN\
        document.getElementById('trafficLight').className = 'traffic-light green';\
        document.getElementById('summaryTitle').innerText = "On Track";\
        document.getElementById('summaryDesc').innerText = "Your glucose is stable.";\
        document.getElementById('todayBar').style.background = "#4caf50";\
    \}\
\
    alert("Meal logged! AI has analyzed your input.");\
    \
    // Reset and go home\
    document.getElementById('mealInput').value = '';\
    switchScreen('dashboard');\
\}\
\
function updateRing(score) \{\
    document.getElementById('scoreDisplay').innerText = score + "%";\
    // Adjust gradient based on score\
    document.getElementById('stabilityRing').style.background = `conic-gradient(#4caf50 $\{score\}%, #e0e0e0 0)`;\
\}}