---
title: 'Washing The Unwashable : On The (Im)possibility of Fairwashing Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ali Shahin Shamsabadi 
  - Mohammad Yaghini
  - Natalie Dullerud
  - Sierra Wyllie
  - Ulrich Aïvodji
  - admin 
  - Sébastien Gambs
  - Nicolas Papernot
# Author notes (optional)
#author_notes:
#- 'Equal contribution'
#- 'Equal contribution'

date: '2022-11-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS*
publication_short: In *NeurIPS*

abstract: The use of black-box models (e.g., deep neural networks) in high-stakes decision making systems, whose internal logic is complex, raises the need for providing explanations about their decisions. Model explanation techniques mitigate this problem by generating an interpretable and high-fidelity surrogate model (e.g., a logistic regressor or decision tree) to explain the logic of black-box models. In this work, we investigate the issue of fairwashing, in which model explanation techniques are manipulated to rationalize decisions taken by an unfair black-box model using deceptive surrogate models. More precisely, we theoretically characterize and analyze fairwashing, proving that this phenomenon is difficult to avoid due to an irreducible factor—the unfairness of the black-box model. Based on the theory developed, we propose a novel technique, called FRAUD-Detect (FaiRness AUDit Detection), to detect fairwashed models by measuring a divergence over subpopulation-wise fidelity measures of the interpretable model. We empirically demonstrate that this divergence is significantly larger in purposefully fairwashed interpretable models than in honest ones. Furthermore, we show that our detector is robust to an informed adversary trying to bypass our detector. The code implementing FRAUD-Detect is available at https://github.com/cleverhans-lab/FRAUD-Detect.



#tags: []

# Display this page in the Featured widget?
featured: true

 # Custom links (uncomment lines below)
 # links:
 # - name: Custom Link
  # url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---



