---
layout: page
title: Project
permalink: /project/
description: Research projects in spintronics, Figure Creator v7, a macrospin magnetization dynamics simulator, and TopDock.
---

## Research {#research}

My research centers on spin-orbit torques, magnonic effects, and spin transport
in magnetic thin film heterostructures.

<div class="figure-row">
  <figure>
    <img src="/assets/images/project/research-field-free.jpg" alt="Field-free Magnetization Switching" />
    <figcaption>Field-free Magnetization Switching</figcaption>
  </figure>
  <figure>
    <img src="/assets/images/project/research-phonon-magnon.jpg" alt="Phonon–Magnon Interaction" />
    <figcaption>Spin–Phonon Interaction</figcaption>
  </figure>
  <figure>
    <img src="/assets/images/project/research-self-torque.jpg" alt="Self-generated Spin Torque via Magnonic Spin Dissipation" />
    <figcaption>Self-generated Spin Torque via Magnonic Spin Dissipation</figcaption>
  </figure>
</div>

## Develop {#develop}

<div class="project-feature">
  <div class="project-feature__header">
    <div class="project-feature__eyebrow">macOS · Version 7</div>
    <h3>Figure Creator</h3>
  </div>
  <img class="project-feature__image" src="/assets/images/project/figure-creator-surface.png" alt="Colorful three-dimensional surface plot created with Figure Creator" />
  <div class="project-feature__body">
    <p class="project-feature__lead">
      A desktop application for turning measurement data into clean,
      publication-ready scientific figures with a live, interactive canvas.
    </p>
    <ul class="project-feature__list">
      <li>2D, polar, 3D, heatmap, surface, bar, and multi-panel figures</li>
      <li>Drag-to-edit layouts, legends, annotations, axes, and colorbars</li>
      <li>Journal size presets, LaTeX labels, error bars, broken axes, and high-resolution export</li>
      <li>English and Korean interface with searchable settings</li>
    </ul>
    <div class="project-downloads">
      <a class="download-btn download-btn--primary" href="https://github.com/shr0eq/shr0eq.github.io/releases/download/figure-creator-v7/FigureCreator-v7-macOS-AppleSilicon.zip">
        Download for macOS <span>ZIP · 67 MB</span>
      </a>
      <a class="download-btn" href="/assets/downloads/figure-creator/Figure_Creator_v7_Manual_EN.pdf">
        English Manual <span>PDF</span>
      </a>
      <a class="download-btn" href="/assets/downloads/figure-creator/Figure_Creator_v7_Manual_KO.pdf">
        Korean Manual <span>PDF</span>
      </a>
    </div>
    <p class="project-feature__note">
      <strong>System requirement:</strong> Apple Silicon Mac (M1 or later).
      The current build is not notarized; follow the first-launch instructions in the manual to allow it in
      <em>System Settings → Privacy &amp; Security</em>.
    </p>
  </div>
</div>

<div class="project-feature project-feature--secondary">
  <div class="project-feature__header">
    <div class="project-feature__eyebrow">In Development · Python</div>
    <h3>Macrospin Simulator</h3>
  </div>
  <div class="project-feature__gallery">
    <figure>
      <img src="/assets/images/project/macrospin-simulator/ima-trajectory.png" alt="Simulated in-plane magnetization trajectory on a Bloch sphere" />
      <figcaption>In-plane magnetization trajectory</figcaption>
    </figure>
    <figure>
      <img src="/assets/images/project/macrospin-simulator/precession-demo.gif" alt="Animated macrospin precession around an applied magnetic field" />
      <figcaption>Macrospin precession dynamics</figcaption>
    </figure>
  </div>
  <div class="project-feature__body">
    <p class="project-feature__lead">
      A desktop simulator for exploring magnetization dynamics within the macrospin approximation.
      It numerically solves the Landau–Lifshitz–Gilbert equation and visualizes precession,
      spin–orbit-torque switching, and time-resolved trajectories.
    </p>
    <p class="project-feature__note">
      Currently under active development.
    </p>
  </div>
</div>

<div class="project-feature project-feature--secondary">
  <div class="project-feature__header">
    <div class="project-feature__eyebrow">macOS · Version 0.1</div>
    <h3>TopDock</h3>
  </div>
  <video class="project-feature__image" autoplay loop muted playsinline
         poster="/assets/images/project/topdock/notchhub-panel.png"
         aria-label="TopDock demo: pushing the cursor into the notch opens a floating panel, browsing a folder, and the panel hides when the cursor leaves">
    <source src="/assets/images/project/topdock/notchhub-demo.mp4" type="video/mp4" />
  </video>
  <div class="project-feature__body">
    <p class="project-feature__lead">
      A native menu-bar utility that turns the MacBook notch into a quick launcher:
      push the cursor into the notch (or press &#8997;Space) and a floating panel of
      your folders and apps appears — launch, browse, and file things away without
      leaving the current app.
    </p>
    <ul class="project-feature__list">
      <li>Trigger by shoving the cursor into the notch, the top-center of external displays, or a global hotkey</li>
      <li>In-panel folder browsing with search, sorting, and Quick Look preview</li>
      <li>Drag &amp; drop both ways — drop a file onto a folder tile to copy it there in one motion</li>
      <li>Multiple workspaces for different sets of folders, Korean and English interface</li>
    </ul>
    <div class="project-downloads">
      <a class="download-btn download-btn--primary" href="/assets/downloads/topdock/TopDock-0.1.0.zip">
        Download for macOS <span>ZIP · 0.6 MB</span>
      </a>
    </div>
    <p class="project-feature__note">
      <strong>System requirement:</strong> Apple Silicon Mac, macOS 14 or later.
      The build is not notarized, so macOS blocks the first launch: open
      <em>System Settings &rarr; Privacy &amp; Security</em>, scroll down, and click <em>Open Anyway</em>.
      Built with SwiftUI/AppKit, assisted by Claude Code.
    </p>
  </div>
</div>
