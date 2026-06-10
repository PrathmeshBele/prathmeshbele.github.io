---
title: 'Projects'
date: 2024-05-19
---

<div class="mx-auto max-w-6xl px-4 sm:px-6 lg:px-8 py-10">

<h2 class="text-4xl font-extrabold text-gray-900 dark:text-white mb-4 text-center">Selected Projects</h2>
<p class="text-center text-gray-500 dark:text-gray-400 max-w-2xl mx-auto mb-16">
A compilation of my research and engineering projects in Deep Learning, Computer Vision, Generative AI, and Graph Neural Networks.
</p>

<div class="space-y-20">

<!-- Project 1 -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-8 md:gap-12 items-center">
<div class="md:col-span-5 md:order-1">
<img src="/uploads/projects/multi_sensor_pano.png" alt="Multi-Sensor Panoramic Synthesis" class="rounded-2xl border border-gray-200/50 dark:border-white/10 shadow-md hover:shadow-xl transition-all duration-300 w-full h-auto">
</div>
<div class="md:col-span-7 md:order-2">
<h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Multi-Sensor Cross-View Panoramic Synthesis</h3>
<p class="text-primary-600 dark:text-primary-400 font-semibold mb-1">Google DeepMind</p>
<p class="text-sm text-gray-500 dark:text-gray-400 italic mb-4">Advisors: Prof. Vinay Namboodiri, Dr. Vaibhav Rajan</p>
<ul class="list-disc pl-5 space-y-2 text-gray-600 dark:text-gray-300">
<li>Built a diffusion model synthesizing physically consistent panoramas from solely low-resolution satellite data.</li>
<li>Internalized HR structural priors via a cyclic critic, eliminating explicit geometry needs at inference.</li>
<li>Bridged polar aerial and spherical ground geometries using a coordinate-aware cross-attention mechanism.</li>
<li>Outperformed explicitly HR-conditioned baselines across all metrics on a global dataset of 550K images.</li>
</ul>
</div>
</div>

<hr class="border-gray-200 dark:border-white/10 my-12">

<!-- Project 2 -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-8 md:gap-12 items-center">
<div class="md:col-span-5 md:order-2">
<img src="/uploads/projects/generative_fusion.png" alt="Cross-View Generative Fusion" class="rounded-2xl border border-gray-200/50 dark:border-white/10 shadow-md hover:shadow-xl transition-all duration-300 w-full h-auto">
</div>
<div class="md:col-span-7 md:order-1">
<h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Cross-View Generative Fusion</h3>
<p class="text-primary-600 dark:text-primary-400 font-semibold mb-1">Google DeepMind</p>
<p class="text-sm text-gray-500 dark:text-gray-400 italic mb-4">Advisors: Dr. Vaibhav Rajan, Prof. Sara Beery</p>
<ul class="list-disc pl-5 space-y-2 text-gray-600 dark:text-gray-300">
<li>Pioneering unified cross-view generative fusion to overcome fine-grained detail loss in decoupled methods.</li>
<li>Bridged a critical data gap by curating a novel dataset temporally aligning Sentinel-2 with agricultural Street View.</li>
<li>Architecting discrete diffusion models to resolve fundamental continuous-discrete latent incompatibilities.</li>
</ul>
</div>
</div>

<hr class="border-gray-200 dark:border-white/10 my-12">

<!-- Project 3 -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-8 md:gap-12 items-center">
<div class="md:col-span-5 md:order-1">
<img src="/uploads/projects/domain_generalization.png" alt="Single Source Open Domain Generalization" class="rounded-2xl border border-gray-200/50 dark:border-white/10 shadow-md hover:shadow-xl transition-all duration-300 w-full h-auto">
</div>
<div class="md:col-span-7 md:order-2">
<h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Single Source Open Domain Generalization</h3>
<p class="text-primary-600 dark:text-primary-400 font-semibold mb-1">IIT Bombay</p>
<p class="text-sm text-gray-500 dark:text-gray-400 italic mb-4">Advisors: Prof. Biplab Banerjee, Prof. Gemma Roig</p>
<ul class="list-disc pl-5 space-y-2 text-gray-600 dark:text-gray-300">
<li>Developed SODG-Net, an end-to-end network outperforming benchmarks by 1-14% in open-domain settings.</li>
<li>Proposed a style synthesis block generating diverse statistical features to effectively simulate novel domains.</li>
<li>Formulated novel weight learning and margin objectives to establish distinct representations for open classes.</li>
</ul>
</div>
</div>

<hr class="border-gray-200 dark:border-white/10 my-12">

<!-- Project 4 -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-8 md:gap-12 items-center">
<div class="md:col-span-5 md:order-2">
<img src="/uploads/projects/crop_classification.png" alt="Crop Classification & Data Curation" class="rounded-2xl border border-gray-200/50 dark:border-white/10 shadow-md hover:shadow-xl transition-all duration-300 w-full h-auto">
</div>
<div class="md:col-span-7 md:order-1">
<h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Crop Classification & Data Curation</h3>
<p class="text-primary-600 dark:text-primary-400 font-semibold mb-1">Google DeepMind</p>
<p class="text-sm text-gray-500 dark:text-gray-400 italic mb-4">Advisor: Alok Talekar</p>
<ul class="list-disc pl-5 space-y-2 text-gray-600 dark:text-gray-300">
<li>Leveraged Gemini to semantically filter Street View imagery, isolating optimal candidates for expert annotation.</li>
<li>Established comprehensive annotation guidelines to curate a high-quality, ground-level crop dataset.</li>
<li>Developed a pipeline augmenting scarce satellite data with robust, timestamped, Street View-derived crop labels.</li>
</ul>
</div>
</div>

<hr class="border-gray-200 dark:border-white/10 my-12">

<!-- Project 5 -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-8 md:gap-12 items-center">
<div class="md:col-span-5 md:order-1">
<img src="/uploads/projects/gnn_mapping.png" alt="Graph Neural Networks for Free-space Mapping" class="rounded-2xl border border-gray-200/50 dark:border-white/10 shadow-md hover:shadow-xl transition-all duration-300 w-full h-auto">
</div>
<div class="md:col-span-7 md:order-2">
<h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Graph Neural Networks for Free-space Mapping</h3>
<p class="text-primary-600 dark:text-primary-400 font-semibold mb-1">MBRDI</p>
<p class="text-sm text-gray-500 dark:text-gray-400 italic mb-4">Advisor: Dr. Laxmikant Sahoo</p>
<ul class="list-disc pl-5 space-y-2 text-gray-600 dark:text-gray-300">
<li>Proposed a novel GNN architecture formulating free-space mapping as a scalable edge-prediction problem [Patent].</li>
<li>Architected a dual-path Graph Attention Network to independently process node and edge features.</li>
<li>Implemented class-aware edge retention via feature fusion, achieving parity with inflexible rule-based legacy systems.</li>
</ul>
</div>
</div>

<hr class="border-gray-200 dark:border-white/10 my-12">

<!-- Project 6 -->
<div class="grid grid-cols-1 md:grid-cols-12 gap-8 md:gap-12 items-center">
<div class="md:col-span-5 md:order-2">
<img src="/uploads/projects/domain_adaptation.png" alt="Incremental Domain Adaptation" class="rounded-2xl border border-gray-200/50 dark:border-white/10 shadow-md hover:shadow-xl transition-all duration-300 w-full h-auto">
</div>
<div class="md:col-span-7 md:order-1">
<h3 class="text-2xl font-bold text-gray-900 dark:text-white mb-2">Incremental Domain Adaptation</h3>
<p class="text-primary-600 dark:text-primary-400 font-semibold mb-1">IIT Bombay</p>
<p class="text-sm text-gray-500 dark:text-gray-400 italic mb-4">Advisors: Prof. Biplab Banerjee, Prof. Gemma Roig</p>
<ul class="list-disc pl-5 space-y-2 text-gray-600 dark:text-gray-300">
<li>Devised a robust solution establishing discriminative, domain-invariant feature spaces under shifting distributions.</li>
<li>Retained critical prior learnings by aligning model outputs and batch-norm parameters for representative proxy data.</li>
<li>Leveraged center loss alongside standard cross-entropy to significantly enhance model prediction confidence.</li>
</ul>
</div>
</div>

</div>

<div class="mt-20 pt-8 border-t border-gray-200 dark:border-white/10 text-center">
<p class="text-xs text-gray-400 dark:text-gray-500">
*Note: Visualizations are AI-generated representations and may not completely align with the actual project outcomes.*
</p>
</div>

</div>ß
