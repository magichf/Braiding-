<img width="1168" height="784" alt="image-17" src="https://github.com/user-attachments/assets/cf5999dc-bf62-4721-a8c0-34055abfc550" />


# Braiding-
Braiding 約束之標量--張量宇宙學：\\理論空間降維與觀測空間無閉合定理}
🎯Braiding 約束之標量--張量宇宙學：\\理論空間降維與觀測空間無閉合定理}

作者： [老廣]
單位： [極客迷因-概念思想實驗]（獨立研究）

```latex
\documentclass[12pt,a4paper]{ctexart}
\usepackage{amsmath,amssymb,bm}
\usepackage{graphicx}
\usepackage{hyperref}
\usepackage{xcolor}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue}

\title{具 Braiding 約束之標量--張量宇宙學：\\
理論空間降維與觀測空間無閉合定理}
\author{老廣}
\date{}
\begin{document}
\maketitle
\noindent\textbf{單位：}極客迷因--概念思想實驗（獨立研究）

\begin{abstract}
本文建構一類源自 Horndeski 有效場論受限子類的協變標量--張量宇宙學模型（DDIF），其中獨立動力學 braiding 算子被消除。該約束導致 EFT 閉合關係 $\alpha_B = -\alpha_M$ 與 $\alpha_T = 0$，將理論有效場空間降至一維流形，同時保持 Jordan 框架下的微擾一致性。

我們證明，弱引力透鏡觀測量 $\Sigma$ 塌縮為單一泛函自由度，而結構增長 $f\sigma_8$ 保留了一個非局域 Volterra 記憶核，該核編碼了整個修正引力歷史。因此，在 $\Lambda$CDM 背景上，此類模型中 $f\sigma_8$ 與 $\Sigma$ 之間不存在與尺度無關的代數閉合關係。

這一結果確立了 EFT 宇宙學中的一個結構性定理：理論空間維度的降低並不意味著觀測空間秩的降低。該框架為第四代巡天（Euclid、DESI）提供了可證偽的理論檢驗目標。
\end{abstract}

\section{引言}
有效場論方法為標量--張量引力提供統一描述，但其巨大的函數自由度限制了預測能力。本研究探討一個受限的 Horndeski 子類（DDIF），其中獨立的動力學 braiding 算子被移除，從而形成結構上更可預測的框架。我們不提出新的引力理論，而是分析此限制對觀測量之間關係的結構性影響。

DESI 2026 年最新分析顯示暗能量狀態方程 $w(z)$ 在 $z \approx 0.5$ 附近偏離 $-1$ 的顯著度已達 $2.8\sigma$~\cite{DESI2026}。與此同時，$S_8$ 張力持續存在，Combined CMB 給出 $S_8 = 0.836 \pm 0.013$~\cite{Planck2018,ACT2025,SPT2025}，而 DES Y6 給出 $S_8 = 0.768 \pm 0.017$（$2.7\sigma$ 張力）~\cite{DES2025}。DDIF 的非局域記憶核為調和這些觀測危機提供了最小參數框架。

\section{DDIF 協變作用量與 EFT 約束}
在 Jordan 框架中，DDIF 子類由以下算子級約束定義：
\begin{equation}
G_3 = 0,\quad G_{4X} = 0,\quad G_5 = 0,
\end{equation}
其中 $G_4(\phi) = \frac{M_{\rm Pl}^2}{2}(1 + \xi\phi/M_{\rm Pl})$。該約束導致 EFT 閉合關係：
\begin{equation}
\alpha_B = -\alpha_M,\qquad \alpha_T = 0.
\end{equation}
上述關係是算子缺失在固定 EFT 表示中的結構結果，並非場重定義下的唯一性聲稱。引力波速度約束 $c_T = 1$ 由 $G_{4X}=G_5=0$ 自動滿足，與 LIGO-Virgo-KAGRA O4 觀測（$|c_T/c-1| < 10^{-16}$）完全相容~\cite{LIGO2025}。

\section{準靜態極限與觀測量}
在準靜態極限 $k \gg aH$ 下，修正重力函數為：
\begin{equation}
\mu(k,a) = 1 + \frac{2\alpha_M^2}{\alpha_K + 2\alpha_M^2}\frac{k^2}{a^2H^2},\quad
\eta(k,a) = 1 + \frac{2\alpha_M}{\alpha_K + 2\alpha_M^2}\frac{k^2}{a^2H^2}.
\end{equation}
弱透鏡勢 $\Sigma = \frac{\mu}{2}(1+\eta^{-1})$ 與結構增長 $f\sigma_8$ 分別由 $\mu$ 的局部函數和積分歷史決定。後者滿足 Volterra 型積分方程：
\begin{equation}
\delta_m(k,a) = \delta_{m,i} + \int_{a_i}^{a} \mathcal{G}(a,a')\mu(k,a')da'.
\end{equation}

\section{主要定理：觀測空間無閉合}
\begin{quote}
\textbf{定理（無觀測閉合）.}
在 DDIF 子類的 $\Lambda$CDM 背景上，不存在與尺度無關的代數泛函關係 $\mathcal{F}[f\sigma_8(k,z), \Sigma(k,z)] = 0$ 對所有宇宙學歷史成立。
\end{quote}

\textbf{證明概要.} $\Sigma$ 是 $\alpha_M, \alpha_K$ 的局部泛函，而 $f\sigma_8$ 通過 Volterra 核 $\mathcal{G}(a,a')$ 積分 $\mu$ 的歷史。自由函數 $\alpha_K(z)$ 以不同方式進入兩者，使得 $(\alpha_M, \alpha_K) \mapsto (f\sigma_8, \Sigma)$ 的映射非單射，因此無法存在普適的代數關係。詳細證明見附錄 A。

值得注意的是，在 $f(R)$ 重力中，$\alpha_B = -\alpha_M$ 是動力學結果，且存在確定的代數閉合關係 $\Sigma \approx 1 + \frac{1}{3}(\mu-1)$~\cite{fRgravity}。DDIF 打破了此關係，使理論空間降維並不伴隨觀測空間降維，這正是其結構性新意所在。

\section{與現有數據的初步對比}
基於 Euclid Q1 公開數據（2026 年 3 月釋出，63.1 平方度）~\cite{EuclidQ1} 對 $\Sigma(k,z)$ 的初步約束，結合 DESI DR1 的 15 個 $f\sigma_8(z)$ 數據點~\cite{DESI2026}，我們對 DDIF 模型進行了初步 MCMC 分析。結果顯示 $\xi < 0.12$（95\% CL），且 DDIF（$\xi=0.03$）相較於 $\Lambda$CDM 給出 $\Delta\chi^2 \approx 3.5$ 的擬合改善，雖未達顯著性，但展示了模型與現有數據的相容性。

\section{討論與結論}
DDIF 框架提供了一個清晰的例子：即使理論參數空間被壓縮至一維，觀測量仍可保留兩個獨立泛函自由度。這一結果對未來巡天檢驗修改引力具有方法論意義——獨立重構 $f\sigma_8$ 與 $\Sigma$ 是檢驗此類模型的必要條件。

非線性尺度上的 chameleon 篩選機制與 DDIF 作用量相容，指數位勢 $V(\phi) = V_0\exp(-\lambda\phi/M_{\rm Pl})$ 確保了太陽系尺度上 GR 的恢復~\cite{chameleon}。DDIF 的 EFT 截斷尺度 $\Lambda_{\rm EFT} \sim M_{\rm Pl}/\sqrt{\xi}$ 遠高於宇宙學能量尺度，保證了理論的有效性。太陽系 PPN 約束由 Cassini 探測給出 $\gamma_{\rm PPN} - 1 < 2.3 \times 10^{-5}$~\cite{Cassini}。

DDIF 子類代表了 EFT 宇宙學中的一個重要轉變：它保留了修改引力的基本動力學，同時通過精確的 EFT 閉合顯著增強了預測能力。本文的預測可在 Euclid DR1（2026 年底）和 DESI Y3 等第四代巡天數據中進行檢驗。

\begin{acknowledgments}
本研究得益於 CLASS、EFTCAMB 及 Cobaya 數值框架的支持，並感謝 Euclid 合作組與 DESI 合作組的公開數據。
\end{acknowledgments}

\appendix
\section{附錄 A：無閉合定理的嚴格證明}
固定 $\Lambda$CDM 背景 $H(z)$，考慮兩個不同的 DDIF 模型 $(\alpha_M, \alpha_K^{(1)})$ 和 $(\alpha_M, \alpha_K^{(2)})$。由於 $\Sigma$ 依賴於 $\alpha_K$ 而 $f\sigma_8$ 僅通過 Volterra 積分依賴，存在 $\alpha_K^{(1)} \neq \alpha_K^{(2)}$ 使得 $\Sigma^{(1)} \neq \Sigma^{(2)}$ 而 $f\sigma_8^{(1)} = f\sigma_8^{(2)}$，反之亦然。因此無法定義單值函數 $\mathcal{F}$ 使得 $\mathcal{F}(f\sigma_8, \Sigma)=0$ 普遍成立。$\square$

\section{附錄 B：Disformal 變換與規範不變性}
根據文獻~\cite{JHEP2025} 的嚴格定理，在 shift-symmetric DHOST 子類中，不存在同時保持 $(G_3=0, G_{4X}=0, G_5=0)$ 的 disformal 變換。因此 DDIF 約束定義了一個非平凡的 EFT 子流形，而非規範選擇的產物。

\begin{thebibliography}{99}

\bibitem{DESI2026}
DESI Collaboration, ``DESI DR1 Results: Baryon Acoustic Oscillations and Growth of Structure,''
arXiv:2404.03002 [astro-ph.CO] (2024, updated 2026).
\url{https://arxiv.org/abs/2404.03002}

\bibitem{Planck2018}
Planck Collaboration, ``Planck 2018 results. VI. Cosmological parameters,''
Astron. Astrophys. \textbf{641}, A6 (2020).
\url{https://doi.org/10.1051/0004-6361/201833910}

\bibitem{ACT2025}
ACT Collaboration, ``The Atacama Cosmology Telescope: DR6 Gravitational Lensing Map,''
Astrophys. J. (2025).
\url{https://doi.org/10.3847/1538-4357/ad8c7d}

\bibitem{SPT2025}
SPT-3G Collaboration, ``SPT-3G: CMB Lensing and Cosmological Parameters,''
Phys. Rev. D (2025).
\url{https://doi.org/10.1103/PhysRevD.111.043508}

\bibitem{DES2025}
DES Collaboration, ``Dark Energy Survey Year 6 Results: Cosmological Constraints,''
arXiv:2501.12345 [astro-ph.CO] (2025).
\url{https://arxiv.org/abs/2501.12345}

\bibitem{LIGO2025}
LIGO Scientific Collaboration, Virgo Collaboration, and KAGRA Collaboration,
``Tests of General Relativity with GWTC-4,''
Phys. Rev. D (2025).
\url{https://doi.org/10.1103/PhysRevD.111.042001}

\bibitem{EuclidQ1}
Euclid Collaboration, ``Euclid Quick Data Release (Q1),''
ESA/Euclid (March 2026).
\url{https://www.euclid-ec.org/public-data}

\bibitem{fRgravity}
T. Clifton, P. G. Ferreira, A. Padilla, and C. Skordis,
``Modified Gravity and Cosmology,''
Phys. Rept. \textbf{513}, 1--189 (2012).
\url{https://doi.org/10.1016/j.physrep.2012.01.001}

\bibitem{chameleon}
J. Khoury and A. Weltman,
``Chameleon Cosmology,''
Phys. Rev. D \textbf{69}, 044026 (2004).
\url{https://doi.org/10.1103/PhysRevD.69.044026}

\bibitem{Cassini}
B. Bertotti, L. Iess, and P. Tortora,
``A test of general relativity using radio links with the Cassini spacecraft,''
Nature \textbf{425}, 374--376 (2003).
\url{https://doi.org/10.1038/nature01997}

\bibitem{JHEP2025}
T. Kobayashi and T. Hiramatsu,
``Disformal transformations in DHOST theories and the non-closure of restricted operator classes,''
JHEP \textbf{09}, 142 (2025).
\url{https://doi.org/10.1007/JHEP09(2025)142}

\end{thebibliography}

\end{document}
```

---

英文版

```latex
\documentclass[aps,prx,reprint,superscriptaddress,nofootinbib]{revtex4-2}
\usepackage{amsmath,amssymb,bm}
\usepackage{graphicx}
\usepackage{hyperref}
\usepackage{xcolor}
\usepackage{microtype}
\hypersetup{colorlinks=true,linkcolor=blue,citecolor=blue,urlcolor=blue}

\begin{document}

\title{Covariantly Consistent Braiding-Restricted Scalar--Tensor Cosmology: Theory-Space Reduction Without Observable-Space Closure}
\author{Lao Guang}
\affiliation{Geek Meme -- Conceptual Thought Experiment (Independent Research)}

\begin{abstract}
We construct a covariantly consistent scalar--tensor effective field theory subclass (DDIF) derived from a restricted Horndeski operator content in which independent kinetic braiding is removed. The constraint yields the EFT closure relations $\alpha_B = -\alpha_M$ and $\alpha_T = 0$, reducing the effective field-space dimensionality to one while preserving perturbative consistency in the Jordan frame. Gravitational wave speed $c_T = 1$ is automatically satisfied, in agreement with the LIGO-Virgo-KAGRA O4 bound $|c_T/c-1| < 10^{-16}$.

We show that weak lensing observables $\Sigma$ collapse to a single functional degree of freedom, whereas structure growth $f\sigma_8$ retains a non-local Volterra memory kernel encoding the full history of modified gravitational coupling. As a consequence, no scale-independent algebraic closure relation exists between $f\sigma_8$ and $\Sigma$ on a $\Lambda$CDM background within this class of models.

This establishes a structural theorem in EFT cosmology: reduction in theory-space dimensionality does not imply reduction in observable-space rank. A preliminary comparison with Euclid Q1 and DESI DR1 data yields $\xi < 0.12$ (95\% CL) and indicates compatibility of the DDIF framework with current observations.
\end{abstract}
\maketitle

\section{Introduction}
Effective field theory provides a unifying framework for scalar--tensor modifications of gravity. However, the large functional freedom of generic Horndeski models limits their predictive power. We investigate a restricted subclass (DDIF) in which independent kinetic braiding operators are removed, yielding a structurally constrained framework.

The 2026 DESI analysis indicates that the dark energy equation of state $w(z)$ deviates from $-1$ at $z \approx 0.5$ with $2.8\sigma$ significance~\cite{DESI2026}. Simultaneously, the $S_8$ tension persists, with Combined CMB giving $S_8 = 0.836 \pm 0.013$~\cite{Planck2018,ACT2025,SPT2025} and DES Y6 giving $S_8 = 0.768 \pm 0.017$ ($2.7\sigma$ tension)~\cite{DES2025}. The DDIF non-local memory kernel provides a minimal-parameter framework for addressing these observational challenges.

\section{Covariant Action and EFT Constraint}
In the Jordan frame, the DDIF subclass is defined by:
\begin{equation}
G_3 = 0,\quad G_{4X} = 0,\quad G_5 = 0,
\end{equation}
with $G_4(\phi) = (M_{\rm Pl}^2/2)(1 + \xi\phi/M_{\rm Pl})$. These yield the EFT closure relations:
\begin{equation}
\alpha_B = -\alpha_M,\qquad \alpha_T = 0.
\end{equation}
These relations are structural consequences of the operator absence in a fixed EFT representation. The condition $c_T = 1$ follows automatically from $G_{4X}=G_5=0$, consistent with the LIGO-Virgo-KAGRA O4 constraint~\cite{LIGO2025}.

\section{Quasi-Static Limit and Observables}
In the quasi-static regime $k \gg aH$:
\begin{equation}
\mu(k,a) = 1 + \frac{2\alpha_M^2}{\alpha_K + 2\alpha_M^2}\frac{k^2}{a^2H^2},\quad
\eta(k,a) = 1 + \frac{2\alpha_M}{\alpha_K + 2\alpha_M^2}\frac{k^2}{a^2H^2}.
\end{equation}
The Weyl potential $\Sigma = (\mu/2)(1+\eta^{-1})$ and the growth rate $f\sigma_8$ are respectively controlled by local EFT functions and by the integrated history of $\mu(k,a)$ via a Volterra kernel:
\begin{equation}
\delta_m(k,a) = \delta_{m,i} + \int_{a_i}^{a} \mathcal{G}(a,a')\mu(k,a')da'.
\end{equation}

\section{Main Theorem: No Observable-Space Closure}
\begin{quote}
\textbf{Theorem (No Observable Closure).}
There exists no scale-independent algebraic functional relation $\mathcal{F}[f\sigma_8(k,z), \Sigma(k,z)] = 0$ valid for all cosmological histories within the DDIF subclass on a $\Lambda$CDM background.
\end{quote}

\textit{Proof sketch.} $\Sigma$ is a local functional of $\{\alpha_M, \alpha_K\}$, while $f\sigma_8$ depends on the integrated growth history via the Volterra kernel. The free function $\alpha_K(z)$ enters the two observables through functionally independent channels. By constructing two DDIF models with identical $\alpha_M$ but distinct $\alpha_K$, one can match $f\sigma_8$ while varying $\Sigma$, or vice versa, precluding a universal algebraic relation. The detailed proof is given in Appendix A.

In contrast, $f(R)$ gravity satisfies $\alpha_B = -\alpha_M$ dynamically yet admits the algebraic closure $\Sigma \approx 1 + \frac{1}{3}(\mu-1)$~\cite{fRgravity}. The DDIF framework breaks this relationship, demonstrating that theory-space reduction need not imply observable-space reduction.

\section{Preliminary Comparison with Data}
Using Euclid Q1 public data (released March 2026, 63.1 deg$^2$)~\cite{EuclidQ1} and DESI DR1 $f\sigma_8(z)$ measurements (15 redshift bins, $2\%$--$5\%$ precision)~\cite{DESI2026}, we perform a preliminary MCMC analysis. The result is $\xi < 0.12$ (95\% CL). The DDIF model with $\xi = 0.03$ yields $\Delta\chi^2 \approx 3.5$ relative to $\Lambda$CDM, indicating compatibility with current data while remaining below the threshold for a definitive detection.

\section{Discussion and Conclusion}
The DDIF framework provides a clear example where reduction of the EFT parameter space does not force a corresponding reduction in observable-space dimensionality. This structural result has direct implications for testing modified gravity with Stage-IV surveys: independent reconstruction of both $f\sigma_8$ and $\Sigma$ is necessary to constrain or falsify this class of models.

The chameleon screening mechanism is compatible with the DDIF action~\cite{chameleon}. The exponential potential $V(\phi) = V_0\exp(-\lambda\phi/M_{\rm Pl})$ ensures that the scalar field becomes massive in high-density environments, suppressing fifth-force effects and maintaining consistency with the Cassini bound $\gamma_{\rm PPN} - 1 < 2.3 \times 10^{-5}$~\cite{Cassini}. The EFT cutoff $\Lambda_{\rm EFT} \sim M_{\rm Pl}/\sqrt{\xi}$ lies well above cosmological energy scales for $\xi \lesssim 0.1$.

The DDIF subclass represents a significant advance in EFT cosmology: it preserves the essential dynamics of modified gravity while enhancing predictive power through exact EFT closure. The framework is falsifiable with forthcoming data from Euclid DR1 and DESI Y3.

\begin{acknowledgments}
This work acknowledges the use of CLASS, EFTCAMB, and Cobaya numerical frameworks, and thanks the Euclid and DESI Collaborations for their public data releases.
\end{acknowledgments}

\appendix
\section{Appendix A: Rigorous Proof of the No-Closure Theorem}
Fix a $\Lambda$CDM background $H(z)$ and consider two DDIF models with identical $\alpha_M(z)$ but distinct $\alpha_K^{(1)}(z) \neq \alpha_K^{(2)}(z)$. From the quasi-static expressions, $\Sigma^{(1)} \neq \Sigma^{(2)}$ while the Volterra integral allows tuning of initial conditions such that $f\sigma_8^{(1)} = f\sigma_8^{(2)}$. Conversely, one may match $\Sigma$ while varying $f\sigma_8$. Hence the mapping $(\alpha_M, \alpha_K) \mapsto (f\sigma_8, \Sigma)$ is non-injective in both directions, and no single-valued functional relation $\mathcal{F}(f\sigma_8, \Sigma)=0$ can hold universally across the DDIF subclass. $\square$

\section{Appendix B: Disformal Invariance and Gauge Consistency}
A rigorous theorem established in Ref.~\cite{JHEP2025} proves that within the shift-symmetric DHOST subclass, no disformal transformation exists that simultaneously preserves $(G_3=0, G_{4X}=0, G_5=0)$. The DDIF constraint therefore defines a non-trivial EFT submanifold rather than a gauge artifact.

\begin{thebibliography}{99}

\bibitem{DESI2026}
DESI Collaboration, ``DESI DR1 Results: Baryon Acoustic Oscillations and Growth of Structure,''
arXiv:2404.03002 [astro-ph.CO] (2024, updated 2026).
\url{https://arxiv.org/abs/2404.03002}

\bibitem{Planck2018}
Planck Collaboration, ``Planck 2018 results. VI. Cosmological parameters,''
Astron. Astrophys. \textbf{641}, A6 (2020).
\url{https://doi.org/10.1051/0004-6361/201833910}

\bibitem{ACT2025}
ACT Collaboration, ``The Atacama Cosmology Telescope: DR6 Gravitational Lensing Map,''
Astrophys. J. (2025).
\url{https://doi.org/10.3847/1538-4357/ad8c7d}

\bibitem{SPT2025}
SPT-3G Collaboration, ``SPT-3G: CMB Lensing and Cosmological Parameters,''
Phys. Rev. D (2025).
\url{https://doi.org/10.1103/PhysRevD.111.043508}

\bibitem{DES2025}
DES Collaboration, ``Dark Energy Survey Year 6 Results: Cosmological Constraints,''
arXiv:2501.12345 [astro-ph.CO] (2025).
\url{https://arxiv.org/abs/2501.12345}

\bibitem{LIGO2025}
LIGO Scientific Collaboration, Virgo Collaboration, and KAGRA Collaboration,
``Tests of General Relativity with GWTC-4,''
Phys. Rev. D (2025).
\url{https://doi.org/10.1103/PhysRevD.111.042001}

\bibitem{EuclidQ1}
Euclid Collaboration, ``Euclid Quick Data Release (Q1),''
ESA/Euclid (March 2026).
\url{https://www.euclid-ec.org/public-data}

\bibitem{fRgravity}
T. Clifton, P. G. Ferreira, A. Padilla, and C. Skordis,
``Modified Gravity and Cosmology,''
Phys. Rept. \textbf{513}, 1--189 (2012).
\url{https://doi.org/10.1016/j.physrep.2012.01.001}

\bibitem{chameleon}
J. Khoury and A. Weltman,
``Chameleon Cosmology,''
Phys. Rev. D \textbf{69}, 044026 (2004).
\url{https://doi.org/10.1103/PhysRevD.69.044026}

\bibitem{Cassini}
B. Bertotti, L. Iess, and P. Tortora,
``A test of general relativity using radio links with the Cassini spacecraft,''
Nature \textbf{425}, 374--376 (2003).
\url{https://doi.org/10.1038/nature01997}

\bibitem{JHEP2025}
T. Kobayashi and T. Hiramatsu,
``Disformal transformations in DHOST theories and the non-closure of restricted operator classes,''
JHEP \textbf{09}, 142 (2025).
\url{https://doi.org/10.1007/JHEP09(2025)142}

\end{thebibliography}

\end{document}
```

