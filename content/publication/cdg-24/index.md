---
title: 'One Gate Scheme to Rule Them All: Introducing a Complex Yet Reduced Instruction Set for Quantum Computing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jianxin Chen
  - Dawei Ding
  - Weiyuan Gong
  - Cupjin Huang
  - Qi Ye

# Author notes (optional)
author_notes:

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM Conference on Architectural Support for Programming Languages and Operating Systems*
publication_short: In *ASPLOS*

abstract: The design and architecture of a quantum instruction set are paramount to the performance of a quantum computer. This work introduces a gate scheme for qubits with $XX+YY$ coupling that directly and efficiently realizes any two-qubit gate up to single-qubit gates. First, this scheme enables high-fidelity execution of quantum operations, especially when decoherence is the primary error source. Second, since the scheme spans the entire $\textbf{SU}(4)$ group of two-qubit gates, we can use it to attain the optimal two-qubit gate count for algorithm implementation. These two advantages in synergy give rise to a quantum Complex yet Reduced Instruction Set Computer (CRISC). Though the gate scheme is compact, it supports a comprehensive array of quantum operations. This may seem paradoxical but is realizable due to the fundamental differences between quantum and classical computer architectures. Using our gate scheme, we observe marked improvements across various applications, including generic $n$-qubit gate synthesis, quantum volume, and qubit routing. Furthermore, the proposed scheme also realizes a gate locally equivalent to the commonly used $\CNOT$ gate with a gate time of $\frac{\pi}{2g}$, where $g$ is the two-qubit coupling. The AshN scheme is also completely impervious to $ZZ$ error, the main coherent error in transversely coupled systems, as the control parameters implementing the gates can be easily adjusted to take the $ZZ$ component into account.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
