---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Wei Li, a principal research scientist at Huawei Foundation Model Department. Currently, I am leading the Multimodal Generation Post-Training team. My research interests broadly encompass efficient systems for large language models and multimodal generation, and reinforcement learning for multimodal generation.  

I received my M.S. degree from Tsinghua University in 2019, co-advised by Prof. Guoqiang Bai and IEEE Fellow [Prof. Zhihua Wang](https://www.ime.tsinghua.edu.cn/info/1010/1746.htm). Since joining Huawei in 2019, I have collaborated closely with [Dr.Xinghao Chen](https://scholar.google.com/citations?user=tuGWUVIAAAAJ&hl=en) and [Dr.Yunhe Wang](https://scholar.google.com/citations?user=isizOkYAAAAJ&hl=en) 

Driven by a passion for bridging cutting-edge algorithms with strict hardware constraints, I have pioneered multiple core technologies that empower intelligent imaging and generative models across tens of millions of flagship devices globally. I have published over 20 papers in top-tier AI venues (including multiple ICLR Spotlight, CVPR, ICML, ACL, and IEEE TIP articles) and hold more than 30 patents. 

> ### 🤝 Join Our Team / Hiring Interns
> We are actively seeking self-motivated interns to work on next-generation multimodal generation systems. If you are passionate about defining the future of ubiquitous generative AI and publishing at top-tier venues, please feel free to drop me an email with your CV.

<h1>🚀 News</h1>
===========                    
**[2026.06]** Honored to serve as a **Virtual Session Chair** for the [LLM Efficiency] track at ACL 2026.                                   
**[2026.05]** Three papers accepted by **ICML 2026** (ES-COT, CSD, [Extra-CoT](https://arxiv.org/pdf/2602.08324)).  
**[2026.04]** One paper accepted by **ACL 2026** ([Dac-KL](https://arxiv.org/pdf/2407.10068)).     
**[2025.11]** One paper accepted by **IEEE TIP** ([Hi-Mamba](https://arxiv.org/pdf/2410.10140?)).   
**[2025.05]** One paper accepted by **IEEE TIP**. ([LIPT](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11008483)).    
**[2025.01]** One paper accepted by **CVPR 2025**.      
**[2025.01]** Three papers accepted by **ICLR 2025**, including ***2 Spotlight([CBQ](https://proceedings.iclr.cc/paper_files/paper/2025/file/15212bd2265c4a3ab0dbc1b1982c1b69-Paper-Conference.pdf), [MipKD](https://proceedings.iclr.cc/paper_files/paper/2025/file/dcdaccb57420cb344b73da90f2281f11-Paper-Conference.pdf))***, and **[AugKD](https://openreview.net/pdf?id=AC3713Fmhx)**！      
**[2024.11]** Two papers accepted by **AAAI 2025** ([GIM](https://arxiv.org/pdf/2406.16531), [DCKD](https://arxiv.org/pdf/2412.08939v1)).     
**[2024.07]** One paper accepted by **ECCV 2024** ([PQ-SAM](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01627.pdf)).        
**[2024.02]** One paper accepted by **CVPR 2024** ([SAM4IR](https://openaccess.thecvf.com/content/CVPR 2024/papers/Zhang_Distilling_Semantic_Priors_from_SAM_to_Efficient_Image_Restoration_Models_CVPR_2024_paper.pdf)).       
**[2023.09]** One paper accepted by **NeurIPS 2024** ([Genimage](https://proceedings.neurips.cc/paper_files/paper/2023/file/f4d4a021f9051a6c18183b059117e8b5-Paper-Datasets_and_Benchmarks.pdf)).     
**[2023.04]** Won the Winner Award in NTIRE Challenge on Image Denoising@**CVPR2023**.              
**[2023.02]** One paper accepted by **CVPR 2023** ([RefSR-NeRF](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_RefSR-NeRF_Towards_High_Fidelity_and_Super_Resolution_View_Synthesis_CVPR_2023_paper.pdf)).     
**[2021.11]** One paper accepted by **AAAI 2022** ([OoDHDR-codec](https://github.com/caolinfeng/OoDHDR-codec/blob/master/Readme.md)).     

## Selected Publications
<hr>
<div style="display: flex; flex-direction: row; align-items: flex-start; margin-bottom: 30px;">
  <div style="flex: 0 0 32%; margin-right: 20px;">
    <img src="/images/mipkd.png" alt="MiPKD Teaser for Image Super-Resolution" style="border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 4px; max-width: 100%; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  </div>
  
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 1.15em; line-height: 1.3;">
      <strong>Knowledge distillation with multi-granularity mixture of priors for image super-resolution</strong>
    </h3>
    
    <p style="margin: 0; font-size: 1.05em;">
      Simiao Li, Yun Zhang, <span style="font-weight: 800;">Wei Li</span><sup>&dagger;</sup>, Hanting Chen, Wenjia Wang, Bingyi Jing, Shaohui Lin, Jie Hu
    </p>
    
    <p style="margin: 8px 0 0 0; font-size: 1.05em;">
      <sup>&dagger;</sup><em>Project Leader & Co-first author, ICLR 2025 (Spotlight)</em> &nbsp;
      
      <a href="https://proceedings.iclr.cc/paper_files/paper/2025/file/dcdaccb57420cb344b73da90f2281f11-Paper-Conference.pdf" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[Paper]</a> &nbsp;
      
      <a href="javascript:void(0)" onclick="var b=document.getElementById('bib-mipkd'); b.style.display=(b.style.display=='none')?'block':'none';" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[BibTeX]</a>
    </p>

    <div id="bib-mipkd" style="display: none; margin-top: 12px; padding: 12px; background-color: rgba(128, 128, 128, 0.08); border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 6px; font-family: monospace; font-size: 0.85em; overflow-x: auto; white-space: pre;">@inproceedings{li2025knowledge,
  title={Knowledge distillation with multi-granularity mixture of priors for image super-resolution},
  author={Li, Simiao and Zhang, Yun and Li, Wei and Chen, Hanting and Wang, Wenjia and Jing, Bingyi and Lin, Shaohui and Hu, Jie},
  booktitle={The Thirteenth International Conference on Learning Representations},
  year={2025}
}</div>
  </div>
</div>

<hr>
<div style="display: flex; flex-direction: row; align-items: flex-start; margin-bottom: 30px;">
  <div style="flex: 0 0 32%; margin-right: 20px;">
    <img src="/images/lipt.png" alt="LIPT Teaser" style="border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 4px; max-width: 100%; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 1.15em; line-height: 1.3;">
      <strong>LIPT: Latency-Aware Image Processing Transformer</strong>
    </h3>
    <p style="margin: 0; font-size: 1.05em;">
      Junbo Qiao, <span style="font-weight: 800;">Wei Li</span><sup>&dagger;</sup>, Haizhen Xie, Hanting Chen, Jie Hu, Shaohui Lin, Jungong Han
    </p>
    <p style="margin: 8px 0 0 0; font-size: 1.05em;">
      <sup>&dagger;</sup><em>Project Leader & Co-first author, IEEE TIP 2025</em> &nbsp;
      <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11008483" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[Paper]</a> &nbsp;
      <a href="https://github.com/Junboooo/LIPT" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[Code]</a> &nbsp;
      <a href="javascript:void(0)" onclick="var b=document.getElementById('bib-lipt'); b.style.display=(b.style.display=='none')?'block':'none';" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[BibTeX]</a>
    </p>
    <div id="bib-lipt" style="display: none; margin-top: 12px; padding: 12px; background-color: rgba(128, 128, 128, 0.08); border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 6px; font-family: monospace; font-size: 0.85em; overflow-x: auto; white-space: pre;">@article{qiao2025lipt,
  title={LIPT: Latency-Aware Image Processing Transformer},
  author={Qiao, Junbo and Li, Wei and Xie, Haizhen and Chen, Hanting and Hu, Jie and Lin, Shaohui and Han, Jungong},
  journal={IEEE Transactions on Image Processing},
  year={2025}
}</div>
  </div>
</div>

<hr>
<div style="display: flex; flex-direction: row; align-items: flex-start; margin-bottom: 30px;">
  <div style="flex: 0 0 32%; margin-right: 20px;">
    <img src="/images/augkd.png" alt="AugKD Teaser" style="border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 4px; max-width: 100%; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 1.15em; line-height: 1.3;">
      <strong>AugKD: Ingenious Augmentations Empower Knowledge Distillation for Image Super-Resolution</strong>
    </h3>
    <p style="margin: 0; font-size: 1.05em;">
      Yun Zhang, <span style="font-weight: 800;">Wei Li</span><sup>&dagger;</sup>, Simiao Li, Hanting Chen, Zhijun Tu, Wenjia Wang, Bingyi Jing, Shaohui Lin, Jie Hu
    </p>
    <p style="margin: 8px 0 0 0; font-size: 1.05em;">
      <sup>&dagger;</sup><em>Project Leader & Co-first author, ICLR 2025</em> &nbsp;
      <a href="https://openreview.net/pdf?id=AC3713Fmhx" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[Paper]</a> &nbsp;
      <a href="javascript:void(0)" onclick="var b=document.getElementById('bib-augkd'); b.style.display=(b.style.display=='none')?'block':'none';" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[BibTeX]</a>
    </p>
    <div id="bib-augkd" style="display: none; margin-top: 12px; padding: 12px; background-color: rgba(128, 128, 128, 0.08); border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 6px; font-family: monospace; font-size: 0.85em; overflow-x: auto; white-space: pre;">@inproceedings{zhang2025augkd,
  title={AugKD: Ingenious Augmentations Empower Knowledge Distillation for Image Super-Resolution},
  author={Zhang, Yun and Li, Wei and Li, Simiao and Chen, Hanting and Tu, Zhijun and Wang, Wenjia and Jing, Bingyi and Lin, Shaohui and Hu, Jie},
  booktitle={The Thirteenth International Conference on Learning Representations},
  year={2025}
}</div>
  </div>
</div>

<hr>
<div style="display: flex; flex-direction: row; align-items: flex-start; margin-bottom: 30px;">
  <div style="flex: 0 0 32%; margin-right: 20px;">
    <img src="/images/refsr-nerf.png" alt="RefSR-NeRF Teaser" style="border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 4px; max-width: 100%; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 1.15em; line-height: 1.3;">
      <strong>RefSR-NeRF: Towards High Fidelity and Super Resolution View Synthesis</strong>
    </h3>
    <p style="margin: 0; font-size: 1.05em;">
      Xudong Huang, <span style="font-weight: 800;">Wei Li</span><sup>&dagger;</sup>, Jie Hu, Hanting Chen, Yunhe Wang
    </p>
    <p style="margin: 8px 0 0 0; font-size: 1.05em;">
      <sup>&dagger;</sup><em>Project Leader & Co-first author, CVPR 2023</em> &nbsp;
      <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_RefSR-NeRF_Towards_High_Fidelity_and_Super_Resolution_View_Synthesis_CVPR_2023_paper.pdf" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[Paper]</a> &nbsp;
      <a href="javascript:void(0)" onclick="var b=document.getElementById('bib-refsr'); b.style.display=(b.style.display=='none')?'block':'none';" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[BibTeX]</a>
    </p>
    <div id="bib-refsr" style="display: none; margin-top: 12px; padding: 12px; background-color: rgba(128, 128, 128, 0.08); border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 6px; font-family: monospace; font-size: 0.85em; overflow-x: auto; white-space: pre;">@inproceedings{huang2023refsr,
  title={RefSR-NeRF: Towards High Fidelity and Super Resolution View Synthesis},
  author={Huang, Xudong and Li, Wei and Hu, Jie and Chen, Hanting and Wang, Yunhe},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2023}
}</div>
  </div>
</div>

<hr>
<div style="display: flex; flex-direction: row; align-items: flex-start; margin-bottom: 30px;">
  <div style="flex: 0 0 32%; margin-right: 20px;">
    <img src="/images/rddm.png" alt="RDDM Teaser" style="border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 4px; max-width: 100%; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 1.15em; line-height: 1.3;">
      <strong>RDDM: Practicing Raw Domain Diffusion Model for Real-World Image Restoration</strong>
    </h3>
    <p style="margin: 0; font-size: 1.05em;">
      Yan Chen, Yi Wen, <span style="font-weight: 800;">Wei Li</span><sup>&dagger;</sup>, Junchao Liu, Yong Guo, Jie Hu, Xinghao Chen
    </p>
    <p style="margin: 8px 0 0 0; font-size: 1.05em;">
      <sup>&dagger;</sup><em>Project Leader, Arxiv 2025</em> &nbsp;
      <a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_RefSR-NeRF_Towards_High_Fidelity_and_Super_Resolution_View_Synthesis_CVPR_2023_paper.pdf" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[Paper]</a> &nbsp;
      <a href="javascript:void(0)" onclick="var b=document.getElementById('bib-rddm'); b.style.display=(b.style.display=='none')?'block':'none';" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[BibTeX]</a>
    </p>
    <div id="bib-rddm" style="display: none; margin-top: 12px; padding: 12px; background-color: rgba(128, 128, 128, 0.08); border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 6px; font-family: monospace; font-size: 0.85em; overflow-x: auto; white-space: pre;">@article{chen2025rddm,
  title={RDDM: Practicing Raw Domain Diffusion Model for Real-World Image Restoration},
  author={Chen, Yan and Wen, Yi and Li, Wei and Liu, Junchao and Guo, Yong and Hu, Jie and Chen, Xinghao},
  journal={arXiv preprint},
  year={2025}
}</div>
  </div>
</div>

<hr>
<div style="display: flex; flex-direction: row; align-items: flex-start; margin-bottom: 30px;">
  <div style="flex: 0 0 32%; margin-right: 20px;">
    <video width="100%" controls autoplay loop muted playsinline style="border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
      <source src="/images/ACL 2026_main-374.mp4" type="video/mp4">
    </video>
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 1.15em; line-height: 1.3;">
      <strong>Multi-Granularity Semantic Revision for Large Language Model Distillation</strong>
    </h3>
    <p style="margin: 0; font-size: 1.05em;">
      Xiaoyu Liu, Yun Zhang, <span style="font-weight: 800;">Wei Li</span><sup>&dagger;</sup>, Xudong Huang, Hanting Chen, Yehui Tang, Jie Hu, Zhiwei Xiong, Yunhe Wang
    </p>
    <p style="margin: 8px 0 0 0; font-size: 1.05em;">
      <sup>&dagger;</sup><em>Project Leader, ACL 2026</em> &nbsp;
      <a href="https://arxiv.org/pdf/2407.10068" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[Paper]</a> &nbsp;
      <a href="javascript:void(0)" onclick="var b=document.getElementById('bib-acl2026'); b.style.display=(b.style.display=='none')?'block':'none';" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[BibTeX]</a>
    </p>
    <div id="bib-acl2026" style="display: none; margin-top: 12px; padding: 12px; background-color: rgba(128, 128, 128, 0.08); border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 6px; font-family: monospace; font-size: 0.85em; overflow-x: auto; white-space: pre;">@inproceedings{liu2026multi,
  title={Multi-Granularity Semantic Revision for Large Language Model Distillation},
  author={Liu, Xiaoyu and Zhang, Yun and Li, Wei and Huang, Xudong and Chen, Hanting and Tang, Yehui and Hu, Jie and Xiong, Zhiwei and Wang, Yunhe},
  booktitle={Proceedings of the Annual Meeting of the Association for Computational Linguistics (ACL)},
  year={2026}
}</div>
  </div>
</div>

<hr>
<div style="display: flex; flex-direction: row; align-items: flex-start; margin-bottom: 30px;">
  <div style="flex: 0 0 32%; margin-right: 20px;">
    <img src="/images/cbq.png" alt="CBQ Teaser" style="border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 4px; max-width: 100%; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 8px; font-size: 1.15em; line-height: 1.3;">
      <strong>CBQ: Cross-Block Quantization for Large Language Models</strong>
    </h3>
    <p style="margin: 0; font-size: 1.05em;">
      Xin Ding, Xiaoyu Liu, Zhijun Tu, Yun Zhang, <span style="font-weight: 800;">Wei Li</span><sup>&dagger;</sup>, Jie Hu, Hanting Chen, Yehui Tang, Zhiwei Xiong, Baoqun Yin, Yunhe Wang
    </p>
    <p style="margin: 8px 0 0 0; font-size: 1.05em;">
      <sup>&dagger;</sup><em>ICLR 2025 (Spotlight)</em> &nbsp;
      <a href="https://proceedings.iclr.cc/paper_files/paper/2025/file/15212bd2265c4a3ab0dbc1b1982c1b69-Paper-Conference.pdf" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[Paper]</a> &nbsp;
      <a href="javascript:void(0)" onclick="var b=document.getElementById('bib-cbq'); b.style.display=(b.style.display=='none')?'block':'none';" style="color: #3B82F6; text-decoration: none; font-weight: bold;">[BibTeX]</a>
    </p>
    <div id="bib-cbq" style="display: none; margin-top: 12px; padding: 12px; background-color: rgba(128, 128, 128, 0.08); border: 1px solid rgba(128, 128, 128, 0.2); border-radius: 6px; font-family: monospace; font-size: 0.85em; overflow-x: auto; white-space: pre;">@inproceedings{ding2025cbq,
  title={CBQ: Cross-Block Quantization for Large Language Models},
  author={Ding, Xin and Liu, Xiaoyu and Tu, Zhijun and Zhang, Yun and Li, Wei and Hu, Jie and Chen, Hanting and Tang, Yehui and Xiong, Zhiwei and Yin, Baoqun and Wang, Yunhe},
  booktitle={The Thirteenth International Conference on Learning Representations},
  year={2025}
}</div>
  </div>
</div>
