---
layout: page
title: Hardware
permalink: /hardware/
order: 2
---

## RGB Matrix Music Visualizer

**Description:** A real-time music visualizer running on a Raspberry Pi 4 with a 64×64 RGB LED matrix. Captures audio from a microphone, runs a Fast Fourier Transform to convert raw bytes to frequency data, and maps it to a rainbow spectrum of animated bars on the matrix.

<div style="max-width: 600px; margin: 20px auto;">
  <div style="position: relative; padding-bottom: 75%; height: 0; overflow: hidden; border-radius: 12px; border: 2px solid #808080; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
    <img 
      src="{{ '/rgb_matrix_demo.gif' | relative_url }}" 
      alt="RGB Matrix Music Visualizer Demo"
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: contain;"
    >
  </div>
</div>

<div style="text-align: center; margin: 20px 0;">
  <a href="https://github.com/andycheng2018/rgb-matrix-music-visualizer" target="_blank" rel="noopener noreferrer" style="display: inline-block; background: #333; color: white; padding: 12px 24px; border-radius: 6px; text-decoration: none; font-weight: 600; transition: 0.3s;" onmouseover="this.style.background='#555'" onmouseout="this.style.background='#333'">
    View Source Code
  </a>
</div>