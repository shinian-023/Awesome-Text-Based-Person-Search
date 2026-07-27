## Table of Contents

- [1️⃣ Taxonomy of TBPS Approaches](#1%EF%B8%8F%E2%83%A3-taxonomy-of-tbps-approaches)
  - [External Knowledge](#external-knowledge)
  - [Learning Objectives](#learning-objectives)
  - [Encoder](#encoder)
  - [Modality Interaction](#modality-interaction)
- [2️⃣ Dataset](#2%EF%B8%8F%E2%83%A3-dataset)
  - [Standard TBPS Benchmarks](#standard-tbps-benchmarks)
  - [Multimodal Retrieval Datasets](#multimodal-retrieval-datasets)
  - [Large-Scale Pre-training Datasets](#large-scale-pre-training-datasets)
  - [Cross-Lingual Datasets](#cross-lingual-datasets)

---

## 1️⃣ Taxonomy of TBPS Approaches

### External Knowledge

#### Pose Knowledge

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Cascade%20Attention%20Network%20for%20Person%20Search%3A%20Both%20Image%20and%20Text-Image%20Similarity%20Selection"><strong>Cascade Attention Network for Person Search: Both Image and Text-Image Similarity Selection</strong></a></td>
      <td align="center" width="10%">CAN</td>
      <td align="center" width="8%">2018</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Pose-guided%20Multi-granularity%20Attention%20Network%20for%20Text-based%20Person%20Search"><strong>Pose-guided Multi-granularity Attention Network for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">PMA</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">AAAI</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Multi-level%20Network%20Based%20on%20Text%20Attention%20and%20Pose-guided%20for%20Person%20Re-ID"><strong>Multi-level Network Based on Text Attention and Pose-guided for Person Re-ID</strong></a></td>
      <td align="center" width="10%">PAMN</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICONIP</td>
    </tr>
  </tbody>
</table>

#### Attribute Knowledge

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Adversarial%20Attribute-Text%20Embedding%20for%20Person%20Search%20with%20Natural%20Language%20Query"><strong>Adversarial Attribute-Text Embedding for Person Search with Natural Language Query</strong></a></td>
      <td align="center" width="10%">AATE</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TMM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Text-based%20Person%20Search%20via%20Attribute-aided%20Matching"><strong>Text-based Person Search via Attribute-aided Matching</strong></a></td>
      <td align="center" width="10%">CMAAM</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">WACV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=ViTAA%3A%20Visual-Textual%20Attributes%20Alignment%20in%20Person%20Search%20by%20Natural%20Language"><strong>ViTAA: Visual-Textual Attributes Alignment in Person Search by Natural Language</strong></a></td>
      <td align="center" width="10%">ViTAA</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ECCV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Heterogenous%20Center%20Alignment%20of%20Dual-path%20Features%20for%20Text-image%20Person%20Re-identification"><strong>Heterogenous Center Alignment of Dual-path Features for Text-image Person Re-identification</strong></a></td>
      <td align="center" width="10%">DP-HCA</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">AIIPCC</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Improving%20Embedding%20Learning%20by%20Virtual%20Attribute%20Decoupling%20for%20Text-based%20Person%20Search"><strong>Improving Embedding Learning by Virtual Attribute Decoupling for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">iVAD</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Neural Computing and Applications</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Efficient%20Text-based%20Person%20Search%20via%20Single-stage%20Identity-guided%20Attribute%20Parsing%20and%20Alignment"><strong>Efficient Text-based Person Search via Single-stage Identity-guided Attribute Parsing and Alignment</strong></a></td>
      <td align="center" width="10%">IAPA</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICPR</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Cross-modal%20Co-occurrence%20Attributes%20Alignments%20for%20Person%20Search%20by%20Language"><strong>Cross-modal Co-occurrence Attributes Alignments for Person Search by Language</strong></a></td>
      <td align="center" width="10%">C2A2</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
  </tbody>
</table>

#### Color Knowledge

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://openaccess.thecvf.com/content/ICCV2021/html/Wu_Language-Guided_Person_Search_via_Color_Reasoning_ICCV_2021_paper.html"><strong>LapsCore: Language-guided Person Search via Color Reasoning</strong></a></td>
      <td align="center" width="10%">LapsCore</td>
      <td align="center" width="8%">2021</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICCV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=CAIBC%3A%20Capturing%20All-round%20Information%20Beyond%20Color%20for%20Text-based%20Person%20Retrieval"><strong>CAIBC: Capturing All-round Information Beyond Color for Text-based Person Retrieval</strong></a></td>
      <td align="center" width="10%">CAIBC</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
  </tbody>
</table>

#### Body Parts Knowledge

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Description-based%20Person%20Search%20with%20Multi-grained%20Matching%20Networks"><strong>Description-based Person Search with Multi-grained Matching Networks</strong></a></td>
      <td align="center" width="10%">Tri-MGF</td>
      <td align="center" width="8%">2021</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Displays</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=BiLMa%3A%20Bidirectional%20Local-matching%20for%20Text-based%20Person%20Re-identification"><strong>BiLMa: Bidirectional Local-matching for Text-based Person Re-identification</strong></a></td>
      <td align="center" width="10%">BiLMa</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICCV Workshops</td>
    </tr>
  </tbody>
</table>

### Learning Objectives

#### Identity (ID) Loss

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Look%20Before%20You%20Leap%3A%20Improving%20Text-based%20Person%20Retrieval%20by%20Learning%20a%20Consistent%20Cross-modal%20Common%20Manifold"><strong>Look Before You Leap: Improving Text-based Person Retrieval by Learning a Consistent Cross-modal Common Manifold</strong></a></td>
      <td align="center" width="10%">LBUL</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Fusing%20Two%20Directions%20in%20Cross-domain%20Adaption%20for%20Real%20Life%20Person%20Search%20by%20Language"><strong>Fusing Two Directions in Cross-domain Adaption for Real Life Person Search by Language</strong></a></td>
      <td align="center" width="10%">FTD</td>
      <td align="center" width="8%">2019</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICCV Workshops</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Relation-aware%20Aggregation%20Network%20with%20Auxiliary%20Guidance%20for%20Text-based%20Person%20Search"><strong>Relation-aware Aggregation Network with Auxiliary Guidance for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">RANAG</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">WWW</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Learning%20Granularity-unified%20Representations%20for%20Text-to-image%20Person%20Re-identification"><strong>Learning Granularity-unified Representations for Text-to-image Person Re-identification</strong></a></td>
      <td align="center" width="10%">LGUR</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
  </tbody>
</table>

#### Matching Loss

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Deep%20Cross-modal%20Projection%20Learning%20for%20Image-Text%20Matching"><strong>Deep Cross-modal Projection Learning for Image-Text Matching</strong></a></td>
      <td align="center" width="10%">CMPM+CMPC</td>
      <td align="center" width="8%">2018</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ECCV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2312.01745"><strong>Cross-modal Adaptive Dual Association for Text-to-image Person Retrieval</strong></a></td>
      <td align="center" width="10%">CADA</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%"><a href="https://github.com/LinDixuan/CADA">project</a></td>
      <td align="center" width="10%">TMM</td>
    </tr>
  </tbody>
</table>

#### Ranking Loss

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Visual-Textual%20Association%20with%20Hardest%20and%20Semi-hard%20Negative%20Pairs%20Mining%20for%20Person%20Search"><strong>Visual-Textual Association with Hardest and Semi-hard Negative Pairs Mining for Person Search</strong></a></td>
      <td align="center" width="10%">HSNM</td>
      <td align="center" width="8%">2019</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Mining%20False%20Positive%20Examples%20for%20Text-based%20Person%20Re-identification"><strong>Mining False Positive Examples for Text-based Person Re-identification</strong></a></td>
      <td align="center" width="10%">MFPE</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
  </tbody>
</table>

#### Adversarial Loss

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Deep%20Adversarial%20Graph%20Attention%20Convolution%20Network%20for%20Text-based%20Person%20Search"><strong>Deep Adversarial Graph Attention Convolution Network for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">A-GANet</td>
      <td align="center" width="8%">2019</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=ASPD-Net%3A%20Self-aligned%20Part%20Mask%20for%20Improving%20Text-based%20Person%20Re-identification%20with%20Adversarial%20Representation%20Learning"><strong>ASPD-Net: Self-aligned Part Mask for Improving Text-based Person Re-identification with Adversarial Representation Learning</strong></a></td>
      <td align="center" width="10%">ASPD-Net</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">EAAI</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=AMEN%3A%20Adversarial%20Multi-space%20Embedding%20Network%20for%20Text-based%20Person%20Re-identification"><strong>AMEN: Adversarial Multi-space Embedding Network for Text-based Person Re-identification</strong></a></td>
      <td align="center" width="10%">AMEN</td>
      <td align="center" width="8%">2021</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">PRCV</td>
    </tr>
  </tbody>
</table>

#### MLM/MIM Loss

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2306.02898"><strong>Towards Unified Text-based Person Retrieval: A Large-scale Multi-Attribute and Language Search Benchmark</strong></a></td>
      <td align="center" width="10%">APTM</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%"><a href="https://github.com/Shuyu-XJTU/APTM">project</a></td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/28585"><strong>Unifying Multi-Modal Uncertainty Modeling and Semantic Alignment for Text-to-Image Person Re-identification</strong></a></td>
      <td align="center" width="10%">MLM</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">AAAI</td>
    </tr>
  </tbody>
</table>

#### Other Loss

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Multiplicative%20Angular%20Margin%20Loss%20for%20Text-based%20Person%20Search"><strong>Multiplicative Angular Margin Loss for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">PSW+MAM</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MMAsia</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=DCEL%3A%20Deep%20Cross-modal%20Evidential%20Learning%20for%20Text-based%20Person%20Retrieval"><strong>DCEL: Deep Cross-modal Evidential Learning for Text-based Person Retrieval</strong></a></td>
      <td align="center" width="10%">DCEL</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%"><a href="https://github.com/CFM-MSG/Code_DCEL">project</a></td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://ieeexplore.ieee.org/document/10274673/"><strong>Multi-granularity Matching Transformer for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">TransTPS</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%"><a href="https://github.com/baolp/TransTPS">project</a></td>
      <td align="center" width="10%">TMM</td>
    </tr>
  </tbody>
</table>

### Encoder

#### CNN-RNN/CNN-BERT Encoders

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://openaccess.thecvf.com/content_cvpr_2017/html/Li_Person_Search_With_CVPR_2017_paper.html"><strong>Person Search with Natural Language Description</strong></a></td>
      <td align="center" width="10%">GNA-RNN</td>
      <td align="center" width="8%">2017</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">CVPR</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Improving%20Text-based%20Person%20Search%20by%20Spatial%20Matching%20and%20Adaptive%20Threshold"><strong>Improving Text-based Person Search by Spatial Matching and Adaptive Threshold</strong></a></td>
      <td align="center" width="10%">PWM+ATH</td>
      <td align="center" width="8%">2018</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">WACV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=A%20Convolutional%20Baseline%20for%20Person%20Re-identification%20Using%20Vision%20and%20Language%20Descriptions"><strong>A Convolutional Baseline for Person Re-identification Using Vision and Language Descriptions</strong></a></td>
      <td align="center" width="10%">VLCCA</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Adversarial%20Representation%20Learning%20for%20Text-to-image%20Matching"><strong>Adversarial Representation Learning for Text-to-image Matching</strong></a></td>
      <td align="center" width="10%">TIMAM</td>
      <td align="center" width="8%">2019</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICCV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=TIPCB%3A%20A%20Simple%20but%20Effective%20Part-based%20Convolutional%20Baseline%20for%20Text-based%20Person%20Search"><strong>TIPCB: A Simple but Effective Part-based Convolutional Baseline for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">TIPCB</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Neurocomputing</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Conditional%20Feature%20Learning%20Based%20Transformer%20for%20Text-based%20Person%20Search"><strong>Conditional Feature Learning Based Transformer for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">CFLT</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TIP</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Dual-path%20Convolutional%20Image-Text%20Embeddings%20with%20Instance%20Loss"><strong>Dual-path Convolutional Image-Text Embeddings with Instance Loss</strong></a></td>
      <td align="center" width="10%">Dual-path CNN</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TOMM</td>
    </tr>
  </tbody>
</table>

#### Transformer-Based Encoders

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Contrastive%20Transformer%20Learning%20with%20Proximity%20Data%20Generation%20for%20Text-based%20Person%20Search"><strong>Contrastive Transformer Learning with Proximity Data Generation for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">PDG</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TCSVT</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Learning%20Semantic-aligned%20Feature%20Representation%20for%20Text-based%20Person%20Search"><strong>Learning Semantic-aligned Feature Representation for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">SAPF</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICASSP</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Text-based%20Person%20Re-ID%20by%20Saliency%20Mask%20and%20Dynamic%20Label%20Smoothing"><strong>Text-based Person Re-ID by Saliency Mask and Dynamic Label Smoothing</strong></a></td>
      <td align="center" width="10%">SMDLS</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICONIP</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2210.10276"><strong>CLIP-driven Fine-grained Text-Image Person Re-identification</strong></a></td>
      <td align="center" width="10%">CFine</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%"><a href="https://github.com/shuanglinyan/CFine">project</a></td>
      <td align="center" width="10%">TIP</td>
    </tr>
  </tbody>
</table>

#### VLM-Based Encoders

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2303.04497"><strong>Exploiting the Textual Potential from Vision-Language Pre-training for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">TP-TPS</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2308.10045"><strong>An Empirical Study of CLIP for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">TBPS-CLIP</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%"><a href="https://github.com/Flame-Chasers/TBPS-CLIP">project</a></td>
      <td align="center" width="10%">AAAI</td>
    </tr>
  </tbody>
</table>

### Modality Interaction

#### Intra-Modality Interaction

##### Visual Intra-modal Interaction

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/28101"><strong>Adaptive Uncertainty-based Learning for Text-based Person Retrieval</strong></a></td>
      <td align="center" width="10%">AUL</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%"><a href="https://github.com/CFM-MSG/Code-AUL">project</a></td>
      <td align="center" width="10%">AAAI</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=EESSO%3A%20Exploiting%20Extreme%20and%20Smooth%20Signals%20via%20Omni-frequency%20Learning%20for%20Text-based%20Person%20Retrieval"><strong>EESSO: Exploiting Extreme and Smooth Signals via Omni-frequency Learning for Text-based Person Retrieval</strong></a></td>
      <td align="center" width="10%">EESSO</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Image and Vision Computing</td>
    </tr>
  </tbody>
</table>

##### Textual Intra-modal Interaction

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Textual%20Dependency%20Embedding%20for%20Person%20Search%20by%20Language"><strong>Textual Dependency Embedding for Person Search by Language</strong></a></td>
      <td align="center" width="10%">TDE</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Refined%20Knowledge%20Transfer%20for%20Language-based%20Person%20Search"><strong>Refined Knowledge Transfer for Language-based Person Search</strong></a></td>
      <td align="center" width="10%">RKT</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TMM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Multi-modal%20Reference%20Learning%20for%20Fine-grained%20Text-to-image%20Retrieval"><strong>Multi-modal Reference Learning for Fine-grained Text-to-image Retrieval</strong></a></td>
      <td align="center" width="10%">MMRef</td>
      <td align="center" width="8%">2025</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TMM</td>
    </tr>
  </tbody>
</table>

##### Dual Intra-modal Interaction

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Learning%20Comprehensive%20Representations%20with%20Richer%20Self%20for%20Text-to-image%20Person%20Re-identification"><strong>Learning Comprehensive Representations with Richer Self for Text-to-image Person Re-identification</strong></a></td>
      <td align="center" width="10%">LCR²S</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=TIPCB%3A%20A%20Simple%20but%20Effective%20Part-based%20Convolutional%20Baseline%20for%20Text-based%20Person%20Search"><strong>TIPCB: A Simple but Effective Part-based Convolutional Baseline for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">TIPCB</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Neurocomputing</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Divide-and-merge%20the%20Embedding%20Space%20for%20Cross-modality%20Person%20Search"><strong>Divide-and-merge the Embedding Space for Cross-modality Person Search</strong></a></td>
      <td align="center" width="10%">DME</td>
      <td align="center" width="8%">2021</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Neurocomputing</td>
    </tr>
  </tbody>
</table>

#### Inter-Modality Interaction

##### Global Feature Interaction

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Improving%20Deep%20Visual%20Representation%20for%20Person%20Re-identification%20by%20Global%20and%20Local%20Image-Language%20Association"><strong>Improving Deep Visual Representation for Person Re-identification by Global and Local Image-Language Association</strong></a></td>
      <td align="center" width="10%">GL-ILA</td>
      <td align="center" width="8%">2018</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ECCV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Person%20Re-identification%20from%20Text%20to%20Image%20Based%20on%20Mutual%20Teaching"><strong>Person Re-identification from Text to Image Based on Mutual Teaching</strong></a></td>
      <td align="center" width="10%">MTReID</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">AIEA</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Granularity-aware%20Hyperbolic%20Representation%20for%20Text-based%20Person%20Search"><strong>Granularity-aware Hyperbolic Representation for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">GAHR</td>
      <td align="center" width="8%">2025</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TIFS</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Improving%20Description-based%20Person%20Re-identification%20by%20Multi-granularity%20Image-Text%20Alignments"><strong>Improving Description-based Person Re-identification by Multi-granularity Image-Text Alignments</strong></a></td>
      <td align="center" width="10%">MIA</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TIP</td>
    </tr>
  </tbody>
</table>

##### Local Feature Interaction

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Cross-modal%20Knowledge%20Adaptation%20for%20Language-based%20Person%20Search"><strong>Cross-modal Knowledge Adaptation for Language-based Person Search</strong></a></td>
      <td align="center" width="10%">CMKA</td>
      <td align="center" width="8%">2021</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TIP</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Text-based%20Person%20Search%20via%20Local-Relational-Global%20Fine-grained%20Alignment"><strong>Text-based Person Search via Local-Relational-Global Fine-grained Alignment</strong></a></td>
      <td align="center" width="10%">CM-LRGNet</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">KBS</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Pedestrian-specific%20Bipartite-aware%20Similarity%20Learning%20for%20Text-based%20Person%20Retrieval"><strong>Pedestrian-specific Bipartite-aware Similarity Learning for Text-based Person Retrieval</strong></a></td>
      <td align="center" width="10%">PBSL</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Multi-level%20Part-aware%20Feature%20Disentangling%20for%20Text-based%20Person%20Search"><strong>Multi-level Part-aware Feature Disentangling for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">MPFD</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICME</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Contextual%20Non-local%20Alignment%20over%20Full-scale%20Representation%20for%20Text-based%20Person%20Search"><strong>Contextual Non-local Alignment over Full-scale Representation for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">NAFS with RVN</td>
      <td align="center" width="8%">2021</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Transformer-based%20Language-Person%20Search%20with%20Multiple%20Region%20Slicing"><strong>Transformer-based Language-Person Search with Multiple Region Slicing</strong></a></td>
      <td align="center" width="10%">T-MRS</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TCSVT</td>
    </tr>
  </tbody>
</table>

##### Multi-Granularity Feature Interaction

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Improving%20Description-based%20Person%20Re-identification%20by%20Multi-granularity%20Image-Text%20Alignments"><strong>Improving Description-based Person Re-identification by Multi-granularity Image-Text Alignments</strong></a></td>
      <td align="center" width="10%">MIA</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TIP</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Hierarchical%20Gumbel%20Attention%20Network%20for%20Text-based%20Person%20Search"><strong>Hierarchical Gumbel Attention Network for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">HGAN</td>
      <td align="center" width="8%">2020</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Asymmetric%20Cross-scale%20Alignment%20for%20Text-based%20Person%20Search"><strong>Asymmetric Cross-scale Alignment for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">ACSA</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TMM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Granularity-aware%20Hyperbolic%20Representation%20for%20Text-based%20Person%20Search"><strong>Granularity-aware Hyperbolic Representation for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">GAHR</td>
      <td align="center" width="8%">2025</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TIFS</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Improving%20Deep%20Visual%20Representation%20for%20Person%20Re-identification%20by%20Global%20and%20Local%20Image-Language%20Association"><strong>Improving Deep Visual Representation for Person Re-identification by Global and Local Image-Language Association</strong></a></td>
      <td align="center" width="10%">GL-ILA</td>
      <td align="center" width="8%">2018</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ECCV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Text-based%20Person%20Search%20via%20Multi-granularity%20Embedding%20Learning"><strong>Text-based Person Search via Multi-granularity Embedding Learning</strong></a></td>
      <td align="center" width="10%">MGEL</td>
      <td align="center" width="8%">2021</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">IJCAI</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Multi-level%20Cross-modality%20Learning%20Framework%20for%20Text-based%20Person%20Re-identification"><strong>Multi-level Cross-modality Learning Framework for Text-based Person Re-identification</strong></a></td>
      <td align="center" width="10%">MCL</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Electronics Letters</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Feature%20Semantic%20Alignment%20and%20Information%20Supplement%20for%20Text-based%20Person%20Search"><strong>Feature Semantic Alignment and Information Supplement for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">ESFE+ISN</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Frontiers in Physics</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Text-based%20Person%20Search%20via%20Local-Relational-Global%20Fine-grained%20Alignment"><strong>Text-based Person Search via Local-Relational-Global Fine-grained Alignment</strong></a></td>
      <td align="center" width="10%">CM-LRGNet</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">KBS</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Image-specific%20Information%20Suppression%20and%20Implicit%20Local%20Alignment%20for%20Text-based%20Person%20Search"><strong>Image-specific Information Suppression and Implicit Local Alignment for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">MANet</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TNNLS</td>
    </tr>
  </tbody>
</table>

##### Proxy Task-Guided Interaction

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Joint%20Token%20and%20Feature%20Alignment%20Framework%20for%20Text-based%20Person%20Search"><strong>Joint Token and Feature Alignment Framework for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">TFAF</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">IEEE SPL</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=See%20Finer%2C%20See%20More%3A%20Implicit%20Modality%20Alignment%20for%20Text-based%20Person%20Retrieval"><strong>See Finer, See More: Implicit Modality Alignment for Text-based Person Retrieval</strong></a></td>
      <td align="center" width="10%">IVT</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ECCV Workshops</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2304.02278"><strong>Calibrating Cross-modal Feature for Text-based Person Searching</strong></a></td>
      <td align="center" width="10%">CMCalib</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Unleashing%20the%20Imagination%20of%20Text%3A%20A%20Novel%20Framework%20for%20Text-to-image%20Person%20Retrieval%20via%20Exploring%20the%20Power%20of%20Words"><strong>Unleashing the Imagination of Text: A Novel Framework for Text-to-image Person Retrieval via Exploring the Power of Words</strong></a></td>
      <td align="center" width="10%">UIT</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=LAIP%3A%20Learning%20Local%20Alignment%20from%20Image-Phrase%20Modeling%20for%20Text-based%20Person%20Search"><strong>LAIP: Learning Local Alignment from Image-Phrase Modeling for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">LAIP</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ICME</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=MARS%3A%20Paying%20More%20Attention%20to%20Visual%20Attributes%20for%20Text-based%20Person%20Search"><strong>MARS: Paying More Attention to Visual Attributes for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">MARS</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Learning%20Transferable%20Pedestrian%20Representation%20from%20Multimodal%20Information%20Supervision"><strong>Learning Transferable Pedestrian Representation from Multimodal Information Supervision</strong></a></td>
      <td align="center" width="10%">VAL-PAT</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">arXiv</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2303.12501"><strong>Cross-modal Implicit Relation Reasoning and Aligning for Text-to-image Person Retrieval</strong></a></td>
      <td align="center" width="10%">IRRA</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%"><a href="https://github.com/anosorae/IRRA">project</a></td>
      <td align="center" width="10%">CVPR</td>
    </tr>
  </tbody>
</table>

##### Large Model-Driven Interaction

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2305.08386"><strong>PLIP: Language-Image Pre-training for Person Representation Learning</strong></a></td>
      <td align="center" width="10%">PLIP</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%"><a href="https://github.com/zplusdragon/plip">project</a></td>
      <td align="center" width="10%">NeurIPS</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://arxiv.org/abs/2309.01420"><strong>Unified Pre-training with Pseudo Texts for Text-to-image Person Re-identification</strong></a></td>
      <td align="center" width="10%">UniPT</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%"><a href="https://github.com/ZhiyinShao-H/UniPT">project</a></td>
      <td align="center" width="10%">ICCV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://openreview.net/forum?id=NndGM6iDip"><strong>Fine-grained Semantic Alignment with Transferred Person-SAM for Text-based Person Retrieval</strong></a></td>
      <td align="center" width="10%">SAP-SAM</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%"><a href="https://github.com/xbdxwyh/SAP-SAM-main">project</a></td>
      <td align="center" width="10%">MM</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Human-centered%20Interactive%20Learning%20via%20MLLMs%20for%20Text-to-image%20Person%20Re-identification"><strong>Human-centered Interactive Learning via MLLMs for Text-to-image Person Re-identification</strong></a></td>
      <td align="center" width="10%">ICL</td>
      <td align="center" width="8%">2025</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">CVPR</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Diverse%20Person%3A%20Customize%20Your%20Own%20Dataset%20for%20Text-based%20Person%20Search"><strong>Diverse Person: Customize Your Own Dataset for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">DP</td>
      <td align="center" width="8%">2024</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">AAAI</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Modeling%20Thousands%20of%20Human%20Annotators%20for%20Generalizable%20Text-to-image%20Person%20Re-identification"><strong>Modeling Thousands of Human Annotators for Generalizable Text-to-image Person Re-identification</strong></a></td>
      <td align="center" width="10%">HAM</td>
      <td align="center" width="8%">2025</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">CVPR</td>
    </tr>
  </tbody>
</table>

#### Hybrid Interaction Approach

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="62%">Title</th>
      <th align="center" width="10%">Model</th>
      <th align="center" width="8%">Date</th>
      <th align="center" width="10%">Link</th>
      <th align="center" width="10%">Venue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=A%20Simple%20and%20Robust%20Correlation%20Filtering%20Method%20for%20Text-based%20Person%20Search"><strong>A Simple and Robust Correlation Filtering Method for Text-based Person Search</strong></a></td>
      <td align="center" width="10%">SRCF</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">ECCV</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Learning%20Aligned%20Image-Text%20Representations%20Using%20Graph%20Attentive%20Relational%20Network"><strong>Learning Aligned Image-Text Representations Using Graph Attentive Relational Network</strong></a></td>
      <td align="center" width="10%">GARN</td>
      <td align="center" width="8%">2021</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TIP</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Improving%20Inconspicuous%20Attributes%20Modeling%20for%20Person%20Search%20by%20Language"><strong>Improving Inconspicuous Attributes Modeling for Person Search by Language</strong></a></td>
      <td align="center" width="10%">ASAMN</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">TIP</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=AXM-Net%3A%20Implicit%20Cross-modal%20Feature%20Alignment%20for%20Person%20Re-identification"><strong>AXM-Net: Implicit Cross-modal Feature Alignment for Person Re-identification</strong></a></td>
      <td align="center" width="10%">AXM-Net</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">IAAI</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=PMG%E2%80%94Pyramidal%20Multi-granular%20Matching%20for%20Text-based%20Person%20Re-identification"><strong>PMG—Pyramidal Multi-granular Matching for Text-based Person Re-identification</strong></a></td>
      <td align="center" width="10%">PMG</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">Applied Sciences</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=SUM%3A%20Serialized%20Updating%20and%20Matching%20for%20Text-based%20Person%20Retrieval"><strong>SUM: Serialized Updating and Matching for Text-based Person Retrieval</strong></a></td>
      <td align="center" width="10%">SUM</td>
      <td align="center" width="8%">2022</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">KBS</td>
    </tr>
    <tr>
      <td align="left" width="62%"><a href="https://scholar.google.com/scholar?q=Multi-granularity%20Separation%20Network%20for%20Text-based%20Person%20Retrieval%20with%20Bidirectional%20Refinement%20Regularization"><strong>Multi-granularity Separation Network for Text-based Person Retrieval with Bidirectional Refinement Regularization</strong></a></td>
      <td align="center" width="10%">MSN-BRR</td>
      <td align="center" width="8%">2023</td>
      <td align="center" width="10%">-</td>
      <td align="center" width="10%">MM</td>
    </tr>
  </tbody>
</table>

---

## 2️⃣ Dataset

T2I: text-to-image retrieval; Bi: bidirectional retrieval; CS: closed-set; PT: pre-training only; Multi: additional modalities beyond RGB images and text.

### Standard TBPS Benchmarks

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="16%">Dataset</th>
      <th align="center" width="6%">Year</th>
      <th align="center" width="8%">IDs</th>
      <th align="center" width="10%">Images</th>
      <th align="center" width="10%">Texts</th>
      <th align="center" width="6%">Lang.</th>
      <th align="center" width="8%">Multi</th>
      <th align="center" width="13%">Source</th>
      <th align="center" width="7%">Protocol</th>
      <th align="center" width="8%">Retrieval</th>
      <th align="center" width="8%">Usage</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="16%"><a href="https://openaccess.thecvf.com/content_cvpr_2017/html/Li_Person_Search_With_CVPR_2017_paper.html"><strong>CUHK-PEDES</strong></a></td>
      <td align="center" width="6%">2017</td>
      <td align="center" width="8%">13,003</td>
      <td align="center" width="10%">40,206</td>
      <td align="center" width="10%">80,412</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="13%">AMT captions</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I</td>
      <td align="center" width="8%">Benchmark</td>
    </tr>
    <tr>
      <td align="left" width="16%"><a href="https://arxiv.org/abs/2107.12666"><strong>ICFG-PEDES</strong></a></td>
      <td align="center" width="6%">2021</td>
      <td align="center" width="8%">4,102</td>
      <td align="center" width="10%">54,522</td>
      <td align="center" width="10%">54,522</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="13%">Identity captions</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I</td>
      <td align="center" width="8%">Benchmark</td>
    </tr>
    <tr>
      <td align="left" width="16%"><a href="https://arxiv.org/abs/2109.05534"><strong>RSTPReid</strong></a></td>
      <td align="center" width="6%">2021</td>
      <td align="center" width="8%">4,101</td>
      <td align="center" width="10%">20,505</td>
      <td align="center" width="10%">41,010</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="13%">Real-world captions</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I</td>
      <td align="center" width="8%">Benchmark</td>
    </tr>
  </tbody>
</table>

### Multimodal Retrieval Datasets

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="16%">Dataset</th>
      <th align="center" width="6%">Year</th>
      <th align="center" width="8%">IDs</th>
      <th align="center" width="10%">Images</th>
      <th align="center" width="10%">Texts</th>
      <th align="center" width="6%">Lang.</th>
      <th align="center" width="8%">Multi</th>
      <th align="center" width="13%">Source</th>
      <th align="center" width="7%">Protocol</th>
      <th align="center" width="8%">Retrieval</th>
      <th align="center" width="8%">Usage</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="16%">TriReID</td>
      <td align="center" width="6%">2022</td>
      <td align="center" width="8%">200</td>
      <td align="center" width="10%">5,600</td>
      <td align="center" width="10%">5,600</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">Sketch</td>
      <td align="center" width="13%">Tri-modal pairs</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I/Bi</td>
      <td align="center" width="8%">Multimodal</td>
    </tr>
    <tr>
      <td align="left" width="16%">Tri-CUHK-PEDES</td>
      <td align="center" width="6%">2023</td>
      <td align="center" width="8%">13,003</td>
      <td align="center" width="10%">40,206</td>
      <td align="center" width="10%">80,440</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">Sketch</td>
      <td align="center" width="13%">Synthetic sketch</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I/Bi</td>
      <td align="center" width="8%">Multimodal</td>
    </tr>
    <tr>
      <td align="left" width="16%">Tri-ICFG-PEDES</td>
      <td align="center" width="6%">2023</td>
      <td align="center" width="8%">4,102</td>
      <td align="center" width="10%">54,522</td>
      <td align="center" width="10%">54,522</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">Sketch</td>
      <td align="center" width="13%">Synthetic sketch</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I/Bi</td>
      <td align="center" width="8%">Multimodal</td>
    </tr>
    <tr>
      <td align="left" width="16%">Tri-RSTPReid</td>
      <td align="center" width="6%">2023</td>
      <td align="center" width="8%">4,101</td>
      <td align="center" width="10%">20,505</td>
      <td align="center" width="10%">41,010</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">Sketch</td>
      <td align="center" width="13%">Synthetic sketch</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I/Bi</td>
      <td align="center" width="8%">Multimodal</td>
    </tr>
  </tbody>
</table>

### Large-Scale Pre-training Datasets

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="16%">Dataset</th>
      <th align="center" width="6%">Year</th>
      <th align="center" width="8%">IDs</th>
      <th align="center" width="10%">Images</th>
      <th align="center" width="10%">Texts</th>
      <th align="center" width="6%">Lang.</th>
      <th align="center" width="8%">Multi</th>
      <th align="center" width="13%">Source</th>
      <th align="center" width="7%">Protocol</th>
      <th align="center" width="8%">Retrieval</th>
      <th align="center" width="8%">Usage</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="16%">MALS</td>
      <td align="center" width="6%">2023</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="10%">1,510,330</td>
      <td align="center" width="10%">1,510,330</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">Attr.</td>
      <td align="center" width="13%">Diffusion+BLIP</td>
      <td align="center" width="7%">PT</td>
      <td align="center" width="8%">Bi</td>
      <td align="center" width="8%">Pre-train</td>
    </tr>
    <tr>
      <td align="left" width="16%">LUPerson-T</td>
      <td align="center" width="6%">2023</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="10%">1.3M</td>
      <td align="center" width="10%">1.3M</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="13%">Auto captions</td>
      <td align="center" width="7%">PT</td>
      <td align="center" width="8%">Bi</td>
      <td align="center" width="8%">Pre-train</td>
    </tr>
    <tr>
      <td align="left" width="16%">SYNTH-PEDES</td>
      <td align="center" width="6%">2023</td>
      <td align="center" width="8%">312,321</td>
      <td align="center" width="10%">4,791,711</td>
      <td align="center" width="10%">12,138,157</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="13%">Auto captions</td>
      <td align="center" width="7%">PT</td>
      <td align="center" width="8%">Bi</td>
      <td align="center" width="8%">Pre-train</td>
    </tr>
    <tr>
      <td align="left" width="16%">LUPerson-TA</td>
      <td align="center" width="6%">2023</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="10%">–</td>
      <td align="center" width="10%">–</td>
      <td align="center" width="6%">EN</td>
      <td align="center" width="8%">Attr.</td>
      <td align="center" width="13%">Image-text-attr.</td>
      <td align="center" width="7%">PT</td>
      <td align="center" width="8%">Bi</td>
      <td align="center" width="8%">Pre-train</td>
    </tr>
  </tbody>
</table>

### Cross-Lingual Datasets

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="16%">Dataset</th>
      <th align="center" width="6%">Year</th>
      <th align="center" width="8%">IDs</th>
      <th align="center" width="10%">Images</th>
      <th align="center" width="10%">Texts</th>
      <th align="center" width="6%">Lang.</th>
      <th align="center" width="8%">Multi</th>
      <th align="center" width="13%">Source</th>
      <th align="center" width="7%">Protocol</th>
      <th align="center" width="8%">Retrieval</th>
      <th align="center" width="8%">Usage</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="left" width="16%">VnPersonSearch</td>
      <td align="center" width="6%">2020</td>
      <td align="center" width="8%">72</td>
      <td align="center" width="10%">445</td>
      <td align="center" width="10%">890</td>
      <td align="center" width="6%">VI</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="13%">Vietnamese captions</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I</td>
      <td align="center" width="8%">Cross-lingual</td>
    </tr>
    <tr>
      <td align="left" width="16%">3000VnPersonSearch</td>
      <td align="center" width="6%">2022</td>
      <td align="center" width="8%">3,000</td>
      <td align="center" width="10%">6,302</td>
      <td align="center" width="10%">12,602</td>
      <td align="center" width="6%">VI</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="13%">Vietnamese captions</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I</td>
      <td align="center" width="8%">Cross-lingual</td>
    </tr>
    <tr>
      <td align="left" width="16%">PRW-TPS-CN</td>
      <td align="center" width="6%">2023</td>
      <td align="center" width="8%">993</td>
      <td align="center" width="10%">11,776</td>
      <td align="center" width="10%">47,102</td>
      <td align="center" width="6%">ZH/EN</td>
      <td align="center" width="8%">–</td>
      <td align="center" width="13%">Bilingual captions</td>
      <td align="center" width="7%">CS</td>
      <td align="center" width="8%">T2I</td>
      <td align="center" width="8%">Cross-lingual</td>
    </tr>
  </tbody>
</table>
