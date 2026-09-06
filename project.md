---
layout: page
title: Project
permalink: /project/
description: Research in magnon and spin-phonon transport, alongside scientific software and research tools developed by Won-Young Choi.
---

## Projects

Explore my work across fundamental spin-transport research and scientific software development.

<div class="project-tabs" role="tablist" aria-label="Project categories" data-project-tabs>
  <button class="project-tab is-active" type="button" role="tab" id="tab-research"
          aria-selected="true" aria-controls="panel-research" tabindex="0">Research</button>
  <button class="project-tab" type="button" role="tab" id="tab-develop"
          aria-selected="false" aria-controls="panel-develop" tabindex="-1">Develop</button>
</div>

<section class="project-tab-panel" id="panel-research" role="tabpanel"
         aria-labelledby="tab-research" data-project-panel="research">
  <article class="research-feature">
    <div class="research-feature__header">
      <div class="project-feature__eyebrow">Antiferromagnets · Magnonics · Spin Torque</div>
      <h3>Magnon Transport</h3>
    </div>
    <div class="research-feature__media">
      <video autoplay loop muted playsinline preload="metadata"
             poster="/assets/images/project/research/magnon-transport-coherent-poster.jpg"
             aria-label="Animation of coherent antiferromagnetic magnon transport with spin polarization parallel to the Néel vector">
        <source src="/assets/images/project/research/magnon-transport-coherent.mp4" type="video/mp4" />
      </video>
    </div>
    <div class="research-feature__body">
        <p class="project-feature__lead">
          Magnons—collective excitations of ordered spins—can carry angular momentum
          through electrically insulating antiferromagnets. My research examines how
          the Néel-vector orientation and magnon coherence govern spin transmission
          across antiferromagnet/ferromagnet heterostructures.
        </p>
        <ul class="project-feature__list research-feature__list">
          <li>Spin-polarization filtering by antiferromagnetic order</li>
          <li>Magnon-mediated spin–orbit torque and magnetization switching</li>
          <li>Low-dissipation transport for energy-efficient spintronic devices</li>
        </ul>
    </div>
  </article>

  <article class="research-feature">
    <div class="research-feature__header">
      <div class="project-feature__eyebrow">Spin–Lattice Coupling · Thermal Transport</div>
      <h3>Spin–Phonon Transport</h3>
    </div>
    <div class="research-feature__media">
      <video autoplay loop muted playsinline preload="metadata"
             poster="/assets/images/project/research/spin-phonon-transport-poster.jpg"
             aria-label="Animation illustrating angular-momentum transfer from electron spin to lattice vibrations">
        <source src="/assets/images/project/research/spin-phonon-transport.mp4" type="video/mp4" />
      </video>
    </div>
    <div class="research-feature__body">
        <p class="project-feature__lead">
          Spin–phonon coupling links electronic spin dynamics to lattice vibrations,
          enabling angular momentum and energy to move between spin and phonon channels.
          I study how this conversion influences nonequilibrium spin flow, damping, and
          thermal transport in magnetic heterostructures.
        </p>
        <ul class="project-feature__list research-feature__list">
          <li>Angular-momentum exchange between spins and the lattice</li>
          <li>Separation of electronic, magnonic, and phononic signals</li>
          <li>Thermal pathways for controlling spin transport and device response</li>
        </ul>
    </div>
  </article>
</section>

<section class="project-tab-panel" id="panel-develop" role="tabpanel"
         aria-labelledby="tab-develop" data-project-panel="develop">
<div class="project-feature">
  <div class="project-feature__header">
    <div class="project-feature__eyebrow">Research Tool · IMA/PMA · Python</div>
    <h3>Second-harmonic Hall SOT Analyzer</h3>
  </div>
  <img class="project-feature__image" src="/assets/images/project/sot-analyzer-gui-en.png" alt="English interface of the second-harmonic Hall SOT Analyzer showing analysis settings and extracted torque efficiencies" />
  <div class="project-feature__body">
    <p class="project-feature__lead">
      A desktop tool for extracting x-, y-, and z-spin damping-like and field-like
      torque efficiencies from angular first- and second-harmonic Hall measurements.
      It supports both in-plane and perpendicular magnetic anisotropy samples.
    </p>
    <p class="project-feature__note">
      The application and source code are available upon request.
    </p>
  </div>
</div>

<div class="project-feature project-feature--secondary">
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
      <a class="download-btn download-btn--primary" href="https://github.com/shr0eq/FigureCreator/releases/download/v7.0.0/FigureCreator-v7-macOS-AppleSilicon.zip">
        Download for macOS <span>ZIP · 67 MB</span>
      </a>
      <a class="download-btn" href="https://github.com/shr0eq/FigureCreator/releases/download/v7.0.0/Figure_Creator_v7_Manual_EN.pdf">
        English Manual <span>PDF</span>
      </a>
      <a class="download-btn" href="https://github.com/shr0eq/FigureCreator/releases/download/v7.0.0/Figure_Creator_v7_Manual_KO.pdf">
        Korean Manual <span>PDF</span>
      </a>
      <a class="download-btn" href="https://github.com/shr0eq/FigureCreator">
        View on GitHub <span>Source · MIT</span>
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
    <div class="project-downloads">
      <a class="download-btn" href="https://github.com/shr0eq/MacrospinSimulator">
        View on GitHub <span>Source · MIT</span>
      </a>
    </div>
    <p class="project-feature__note">
      Currently under active development — the AFM (antiferromagnet) mode is
      incomplete; the FM feature set is validated and stable.
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
      <a class="download-btn download-btn--primary" href="https://github.com/shr0eq/TopDock/releases/download/v0.1.0/TopDock-0.1.0.zip">
        Download for macOS <span>ZIP · 0.6 MB</span>
      </a>
      <a class="download-btn" href="https://github.com/shr0eq/TopDock">
        View on GitHub <span>Source · MIT</span>
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
</section>

<script>
(function () {
  var tablist = document.querySelector('[data-project-tabs]');
  if (!tablist) return;

  var tabs = Array.prototype.slice.call(tablist.querySelectorAll('[role="tab"]'));
  var panels = Array.prototype.slice.call(document.querySelectorAll('[data-project-panel]'));

  function activate(tab, updateHash) {
    tabs.forEach(function (item) {
      var selected = item === tab;
      item.classList.toggle('is-active', selected);
      item.setAttribute('aria-selected', selected ? 'true' : 'false');
      item.setAttribute('tabindex', selected ? '0' : '-1');
    });

    panels.forEach(function (panel) {
      var selected = panel.id === tab.getAttribute('aria-controls');
      panel.hidden = !selected;
      panel.querySelectorAll('video').forEach(function (video) {
        if (selected) {
          var playAttempt = video.play();
          if (playAttempt && playAttempt.catch) playAttempt.catch(function () {});
        } else {
          video.pause();
        }
      });
    });

    if (updateHash && window.history && window.history.replaceState) {
      window.history.replaceState(null, '', '#' + tab.id.replace('tab-', ''));
    }
  }

  tabs.forEach(function (tab, index) {
    tab.addEventListener('click', function () { activate(tab, true); });
    tab.addEventListener('keydown', function (event) {
      var targetIndex = index;
      if (event.key === 'ArrowRight') targetIndex = (index + 1) % tabs.length;
      else if (event.key === 'ArrowLeft') targetIndex = (index - 1 + tabs.length) % tabs.length;
      else if (event.key === 'Home') targetIndex = 0;
      else if (event.key === 'End') targetIndex = tabs.length - 1;
      else return;
      event.preventDefault();
      tabs[targetIndex].focus();
      activate(tabs[targetIndex], true);
    });
  });

  tablist.classList.add('is-ready');
  var requested = window.location.hash === '#develop' ? tabs[1] : tabs[0];
  activate(requested, false);
}());
</script>
