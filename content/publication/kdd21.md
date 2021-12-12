+++
title = "Mutual Information Preserving Back-propagation Learn to Invert for Faithful Attribution"
date = 2021-06-05T00:00:03
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Huiqi Deng", "Na Zou", "Weifu Chen", "Guocan Feng", "Mengnan Du", "Xia Hu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "ACM SIGKDD Conference on Knowledge Discovery and Data Mining"
publication_short = "KDD 2021"

# Abstract and optional shortened version.
abstract = "Recent studies have shown that state-of-the-art DNNs are not always credible, despite their impressive performance on the hold-out test set of a variety of tasks. These models tend to exploit dataset shortcuts to make predictions, rather than learn the underlying task. The non-credibility could lead to low generalization, adversarial vulnerability, as well as algorithmic discrimination of the DNN models. In this paper, we propose CREX in order to develop more credible DNNs. The high-level idea of CREX is to encourage DNN models to focus more on evidences that actually matter for the task at hand and to avoid overfitting to data-dependent shortcuts. Specifically, in the DNN training process, CREX directly regularizes the local explanation with expert rationales, i.e., a subset of features highlighted by domain experts as justifications for predictions, to enforce the alignment between local explanations and rationales. Even when rationales are not available, CREX still could be useful by requiring the generated explanations to be sparse. In addition, CREX is widely applicable to different network architectures, including CNN, LSTM and attention model. Experimental results on several text classification datasets demonstrate that CREX could increase the credibility of DNNs. Comprehensive analysis further shows three meaningful improvements of CREX: (1) it significantly increases DNN accuracy on new and previously unseen data beyond test set, (2) it enhances fairness of DNNs in terms of equality of opportunity metric and reduce models’ discrimination toward certain demographic group, and (3) it promotes the robustness of DNN models with respect to adversarial attack. These experimental results highlight the advantages of the increased credibility by CREX."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/2104.06629.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
