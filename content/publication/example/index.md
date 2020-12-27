---
abstract: In this paper, we propose an efficient hyperplane generation technique
  to classify human activity from combination of events and sequence information
  obtained from multiple-event sensors. By generating hyperplane efficiently,
  our machine learning algorithm classify with less memory and run time than the
  LSVM (Linear Support Vector Machine) for embedded system. Because the fact
  that light weight and high speed algorithm is one of the most critical issue
  in the IoT, the study can be applied to smart home to predict human activity
  and provide related services. Our approach is based on reducing numbers of
  hyperplanes and utilizing robust string comparing algorithm. The proposed
  method results in reduction of memory consumption compared to the conventional
  ML (Machine Learning) algorithms; 252 times to LSVM and 34,033 times to LSTM
  (Long Short-Term Memory), although accuracy is decreased slightly. Thus our
  method showed outstanding performance on accuracy per hyperplane; 240 times to
  LSVM and 30,520 times to LSTM. The binarized image is then divided into
  groups, where each groups are converted to binary number, in order to reduce
  the number of comparison done in runtime process. The binary numbers are then
  converted to string. The test data is evaluated by converting to string and
  measuring similarity between hyperplanes using Levenshtein algorithm, which is
  a robust dynamic string comparing algorithm. This technique reduces runtime
  and enables the proposed algorithm to become 27% faster than LSVM, and 90%
  faster than LSTM.
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - admin
  - Kim Boguk
  - Mun Changil
  - Lee Dohyun
  - Kwak Junho
  - Park Daejin
  - Jeong Yoosoo
author_notes:
  - First Author
  - Second Author
  - Second Author
  - Second Author
  - Second Author
  - Second Author
  - Corresponding Author
publication: Journal of Embedded Systems and Applications (대한임베디드공학회논문지)
summary: ""
url_dataset: ""
url_project: ""
publication_short: IEMEK
url_source: ""
url_video: ""
title: Efficient Hyperplane Generation Techniques for Human Activity
  Classification in Multiple-Event Sensors Based Smart Home
subtitle: 다중 이벤트 센서 기반 스마트 홈에서 사람 행동 분류를 위한 효율적 의사결정평면 생성기법
doi: ""
featured: true
tags: []
categories:
  - Domesitic
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
