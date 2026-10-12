<!-- Colours match the portfolio: slate #0f172a, cyan #38bdf8, violet #a78bfa -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&height=170&color=0:0f172a,55:1e3a5f,100:38bdf8&text=Khang%20Tran&fontColor=ffffff&fontSize=48&fontAlignY=36&desc=Machine%20Learning%20Engineer%20%7C%20Paris&descAlignY=58&descSize=16" alt="Khang Tran" width="100%"/>
</p>

<p align="center">
  <a href="https://tmkhang1999.github.io">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=38BDF8&center=true&vCenter=true&width=640&lines=Computer+Vision+%26+LLM+Systems;2+years+shipping+ML+to+production;Best+Student+Paper+%40+IS%26T+EI+2026;MSc+COSI+(Erasmus+Mundus)+-+NTNU+%2F+UJM+%2F+UEF" alt="Computer Vision and LLM Systems"/>
  </a>
</p>

<p align="center">
  <a href="https://tmkhang1999.github.io"><img src="https://img.shields.io/badge/Portfolio-0f172a?style=for-the-badge&logo=googlechrome&logoColor=38bdf8" alt="Portfolio"/></a>
  <a href="https://tmkhang1999.github.io/research.html"><img src="https://img.shields.io/badge/Research-0f172a?style=for-the-badge&logo=googlescholar&logoColor=a78bfa" alt="Research"/></a>
  <a href="https://www.linkedin.com/in/khangtm99"><img src="https://img.shields.io/badge/LinkedIn-0f172a?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iIzM4YmRmOCIgZD0iTTIwLjQ1IDIwLjQ1aC0zLjU2di01LjU3YzAtMS4zMy0uMDItMy4wNC0xLjg1LTMuMDQtMS44NSAwLTIuMTQgMS40NS0yLjE0IDIuOTR2NS42N0g5LjM1VjloMy40MXYxLjU2aC4wNWMuNDgtLjkgMS42NC0xLjg1IDMuMzctMS44NSAzLjYgMCA0LjI3IDIuMzcgNC4yNyA1LjQ2djYuMjh6TTUuMzQgNy40M2EyLjA2IDIuMDYgMCAxIDEgMC00LjEzIDIuMDYgMi4wNiAwIDAgMSAwIDQuMTN6TTcuMTIgMjAuNDVIMy41NlY5aDMuNTZ2MTEuNDV6TTIyLjIyIDBIMS43N0MuNzkgMCAwIC43NyAwIDEuNzN2MjAuNTRDMCAyMy4yMy43OSAyNCAxLjc3IDI0aDIwLjQ1Yy45OCAwIDEuNzgtLjc3IDEuNzgtMS43M1YxLjczQzI0IC43NyAyMy4yIDAgMjIuMjIgMHoiLz48L3N2Zz4%3D" alt="LinkedIn"/></a>
  <a href="mailto:khangtm99@gmail.com"><img src="https://img.shields.io/badge/Email-0f172a?style=for-the-badge&logo=gmail&logoColor=a78bfa" alt="Email"/></a>
</p>

---

### About

Machine Learning Engineer with 2 years of production experience, building LLM and computer-vision systems in Python.  
Erasmus Mundus MSc in Computational Colour and Spectral Imaging (NTNU, Norway / UJM, France / UEF, Finland, 2026), admitted 1st of 198 applicants.  
BSc in Computer Science, SUNY Oswego, Summa Cum Laude.

### Highlights

- **Best Student Paper Award, IS&T Electronic Imaging 2026.** Co-authored [the paper](https://doi.org/10.2352/EI.2026.38.12.GENAI-179) from my DXOMARK internship: a vision-language model adapted to score portrait noise and texture (SRCC 0.91 / 0.93).
- **Multi-agent assistant in production (Vitex).** LangGraph agents with RAG on Qdrant and text-to-SQL, serving hundreds of requests per day. Cut the agent failure rate from about 15% to about 5% by reading production traces.
- **Document extraction at scale (Vitex).** Self-hosted Qwen3-VL-8B on vLLM reads handwritten Japanese forms at 2,000 images per hour with at least 92% field-level accuracy, and sends uncertain results to a second check instead of trusting them.
- **Model serving (Viettel).** Face-recognition models served on Kubernetes with NVIDIA Triton, dynamic batching and runtime model loading.

---

### Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://tmkhang1999.github.io/CIAI/"><img src="https://tmkhang1999.github.io/images/research/ciai-thumb.jpg" alt="CIAI: albedo recovered under different light" width="100%"/></a>
      <br/><b><a href="https://tmkhang1999.github.io/CIAI/">CIAI</a></b> <sub>MSc thesis, 2026</sub>
      <br/><sub>Training strategy for intrinsic image decomposition: two photos of one scene under different light must give the same albedo. 39% lower luminance-stability error on MID, with about 70x fewer trainable parameters than a diffusion baseline.</sub>
      <br/><sub><a href="https://tmkhang1999.github.io/CIAI/">Page</a> / <a href="https://github.com/tmkhang1999/CIAI">Code</a></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://doi.org/10.2352/EI.2026.38.12.GENAI-179"><img src="https://tmkhang1999.github.io/images/research/deqa-thumb.jpg" alt="Portrait quality: noise versus texture" width="100%"/></a>
      <br/><b><a href="https://doi.org/10.2352/EI.2026.38.12.GENAI-179">Attribute-specific portrait quality</a></b> <sub>DXOMARK, 2025</sub>
      <br/><sub>Adapted DeQA-Score from one overall quality score to separate noise and texture scores for camera portrait mode. Best Student Paper Award, IS&T EI 2026.</sub>
      <br/><sub><a href="https://doi.org/10.2352/EI.2026.38.12.GENAI-179">Paper</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://tmkhang1999.github.io/HyRES-Residual-Enhanced-Hybrid-Image-Compression/"><img src="https://tmkhang1999.github.io/images/research/hyres-thumb.jpg" alt="HyRES: JPEG quality 1 versus HyRES" width="100%"/></a>
      <br/><b><a href="https://tmkhang1999.github.io/HyRES-Residual-Enhanced-Hybrid-Image-Compression/">HyRES</a></b> <sub>UJM, 2025</sub>
      <br/><sub>Keeps a quality-1 JPEG as the base layer and codes only the residual with a small learned codec. 37.41 dB at 1.56 bpp on Kodak, 2.1 dB above JPEG at the same file size.</sub>
      <br/><sub><a href="https://tmkhang1999.github.io/HyRES-Residual-Enhanced-Hybrid-Image-Compression/">Page</a> / <a href="https://github.com/tmkhang1999/HyRES-Residual-Enhanced-Hybrid-Image-Compression">Code</a></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/tmkhang1999/TextMAE-Image-Compression"><img src="https://tmkhang1999.github.io/images/research/textmae-thumb.jpg" alt="TextMAE: patches, MAE and codec, decoded image" width="100%"/></a>
      <br/><b><a href="https://github.com/tmkhang1999/TextMAE-Image-Compression">TextMAE</a></b> <sub>Mentored project</sub>
      <br/><sub>Sends only the informative image patches plus a one-sentence caption; a Masked Autoencoder and a caption-guided diffusion refiner rebuild the rest. Mentored by Dr. Thang Nguyen.</sub>
      <br/><sub><a href="https://github.com/tmkhang1999/TextMAE-Image-Compression">Code</a></sub>
    </td>
  </tr>
</table>

Also: [CV-JD Matching](https://github.com/tmkhang1999/CV-JD-Matching), an internal HR tool that ranks candidates against a job description (LLM structured extraction, PostgreSQL + pgvector, optional LLM reranking with explanations).

---

### Tools I use

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,fastapi,docker,kubernetes,aws,postgres,redis,rabbitmq&perline=10" alt="Python, PyTorch, TensorFlow, FastAPI, Docker, Kubernetes, AWS, PostgreSQL, Redis, RabbitMQ"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square" alt="LangSmith"/>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square" alt="Qdrant"/>
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector"/>
  <img src="https://img.shields.io/badge/vLLM-30A2FF?style=flat-square" alt="vLLM"/>
  <img src="https://img.shields.io/badge/NVIDIA_Triton-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA Triton"/>
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"/>
  <img src="https://img.shields.io/badge/LoRA_fine--tuning-0f172a?style=flat-square" alt="LoRA fine-tuning"/>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:38bdf8,45:1e3a5f,100:0f172a" alt="" width="100%"/>
</p>
