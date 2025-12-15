# Assignment-growthX
Tech used - HTML, CSS , BOOTSTRAP
<!--
====================
CSS REFERENCE NOTES
====================

1. CLIP-PATH ANIMATION (funnel-fill)
   - Initial: polygon(0 0, 0 0, 0 100%, 0 100%) → Hidden (zero width)
   - Final: polygon(0 0, 100% 0, 100% 100%, 0 100%) → Fully visible
   - Animation: fillDiagonal 1s ease-out 1s forwards

2. STROKE-DASHARRAY & STROKE-DASHOFFSET (funnel-outline)
   - stroke-dasharray: 100 → Dash pattern length
   - stroke-dashoffset: 100 → Hides entire stroke initially
   - Animation: drawLine 1.8s ease-out forwards → Draws from bottom center up both sides

3. TRANSFORM PROPERTIES (star)
   - Initial: translate(-150px, -80px) rotate(-350deg) scale(0.4)
   - Final: translate(0, 0) rotate(0) scale(1)
   - Creates slide-in effect from upper-left with spin

4. ANIMATIONS USED
   - starSlide: 1.8s ease-out forwards → Star entrance
   - starGlow: 3s ease-in-out 2.5s infinite → Pulsing glow after entrance
   - drawLine: 1.8s ease-out forwards → Funnel outline drawing
   - fillDiagonal: 1s ease-out 1s forwards → Funnel fill reveal
   - slideUp: 1s ease-out 2.2s forwards → Text entrance
   - fadeOut: 1.0s ease-out 4s forwards → Logo exit

5. BACKGROUND-CLIP: TEXT (brand-text)
   - Gradient: linear-gradient(180deg, #ffffff 0%, #d4d4d4 50%, #acacac 100%)
   - background-clip: text + color: transparent → Shows gradient through text

6. SVG PATH COMMANDS
   - Star: M50 0 Q50 50 100 50 Q50 50 50 100 Q50 50 0 50 Q50 50 50 0Z (4-point star)
   - Funnel outline left: M50 50 Q50 0 0 0 (bottom center → top left)
   - Funnel outline right: M50 50 Q50 0 100 0 (bottom center → top right)
   - Funnel fill: M0 0 L100 0 Q50 0 50 50 Q50 0 0 0Z (full shape)

7. DROP-SHADOW FILTER (star)
   - Base: drop-shadow(0 0 8px rgba(255, 255, 255, 0.2))
   - Glow pulse: drop-shadow(0 0 12px rgba(255, 255, 255, 0.3))
-->

