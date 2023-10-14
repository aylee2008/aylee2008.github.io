---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

### On Consistency Training for Language-Based Image Editing Interface
Youngwon Lee\*, Ayoung Lee\*, Yeonjoon Jung, Seung-won Hwang \
*IJCNLP-AACL 2023, Second Workshop on Natural Language Interfaces*

<details>
<p><b>Abstract</b>
This paper studies the training of an image
editing interface using language instructions,
without requiring expensive human annotations.
Such a process involves making necessary changes while preserving the original
content as required. For example, when learning an instruction like "change the suitcase to
a wine glass," the editing model should be provided with a pair of images with a suitcase and a wine glass, respectively, where the two images share the common background. To obtain
such training data, the existing approach capitalizes on a large pretrained language model in tandem with a text-to-image model. Together,
they generate a pair of images from the edited
caption, derived from the original caption and
the instruction. Although this process imposes
cross-attention based regulation, towards effectively constraining the Euclidean distance between the images, we posit that this control is
still somewhat weak, insufficient for adequately
steering the editing interface model in distinguishing where to modify and where to preserve. Our distinctive approach lies in enforcing greater consistency through the utilization of automated object detection and inpainting
within a unified pipeline, thereby ensuring the
preservation of context. The robust empirical
results obtained with our proposed method can
be attributed to enforcing "cycle consistency."
This signifies that the reverse editing instruction
should possess the capability to reconstruct the
original image. Our code is publicly available
at <a href="https://github.com/aylee2008/ConsEdit">github.com/aylee2008/ConsEdit</a>.
</p>
</details>

