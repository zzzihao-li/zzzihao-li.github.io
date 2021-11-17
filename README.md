---
pageClass: home-page
# some data for the components

name: Zihao Li
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/zzzihao-li
  
  - title: google scholar
    icon: "/icons/google-scholar.svg"
    link: https://scholar.google.com/citations?user=B-Vg8FYAAAAJ

  - title: researchgate
    icon: "/icons/researchgate.svg"
    link: https://www.researchgate.net/profile/Zihao-Li-36

cv: /files/Personal_CV.pdf
bio: PhD Student at The Hong Kong Polytechnic University
email: cszhli[at]comp.polyu.edu.hk
---

<ProfileSection :frontmatter="$page.frontmatter" />

## Biography

Zihao Li received his B.S. and M.S. degrees from University of Electronic Science and Technology of China. He is currently working towards the PhD degree with the Department of Computing, The Hong Kong Polytechnic University, under the supervision of [Dr. Daniel Xiapu Luo](https://www4.comp.polyu.edu.hk/~csxluo/). His current research interests include Blockchain, Smart Contracts. He has received several best paper awards (e.g., INFOCOM'18, ISPEC'17, etc.) and a best paper nominee from ESEM'19.


## Education & Experiences

- **Ph.D Candidate, Department of Computing, The Hong Kong Polytechnic University** <br/>
01/2021 - Present

- **Master Degree in University of Electronic Science and Technology of China** <br/>
09/2017 - 06/2020

- **Bachelor Degree in University of Electronic Science and Technology of China** <br/>
09/2013 - 06/2017

## Publications

<ProjectCard hideBorder=true>

  **SigRec: Automatic Recovery of Function Signatures in Smart Contracts**
  
  T. Chen, **Z. Li**, X. Luo, X.Wang, T.Wang, Z. He, K. Fang, Y. Zhang, H. Zhu, H Li, Y Cheng, and X. Zhang

  *IEEE Transactions on Software Engineering (TSE), 2021 (also appear at the Journal First Session of the 36th IEEE/ACM International Conference on Automated Software Engineering (ASE)).*

</ProjectCard>

<ProjectCard hideBorder=true>

  **Understanding Ethereum via Graph Analysis**
  
  T. Chen, Y. Zhu, **Z. Li**, J. Chen, X. Li, X. Luo, X. Lin, and X. Zhang

  *Proc. of IEEE International Conference on Computer Communications (INFOCOM), Honolulu, USA, April 2018. (**Best Paper Award**)*

</ProjectCard>

<ProjectCard hideBorder=true>

  **Towards Saving Money in Using Smart Contracts**
  
  T. Chen, **Z. Li**, H. Zhou, J. Chen, X. Luo, X. Li, and X. Zhang

  *Proc. of 40th IEEE International Conference on Software Engineering (ICSE) (NIER), pp. 81-84, Gothenburg, Sweden, May 2018.*

</ProjectCard>

<ProjectCard hideBorder=true>

  **Understanding Ethereum via Graph Analysis**
  
  T. Chen, **Z. Li**, Y. Zhu, J. Chen, X. Luo, J. Lui, X. Lin, and X. Zhang

  *ACM Transactions on Internet Technology (TOIT), 2020.*

</ProjectCard>

<ProjectCard hideBorder=true>

  **TokenScope: Automatically Detecting Inconsistent Behaviors of Cryptocurrency Tokens in Ethereum**
  
  T. Chen, Y. Zhang, **Z. Li**, X. Luo, T. Wang, R. Cao, X. Xiao, and X. Zhang

  *Proc. of the 26th ACM Conference on Computer and Communications Security (CCS), London, UK, November 2019.*

</ProjectCard>

<ProjectCard hideBorder=true>

  **A Large-Scale Empirical Study on Control Flow Identification of Smart Contracts**
  
  T. Chen, **Z. Li**, Y. Zhang, X. Luo, T. Wang, T. Hu, X. Xiao, D. Wang, J. Huang, and X. Zhang

  *Proc. of the International Symposium on Empirical Software Engineering and Measurement (ESEM), Porto de Galinhas, Brazil, September 2019. (**Best Paper Nominee**)*

</ProjectCard>

<ProjectCard hideBorder=true>

  **DataEther: Data Exploration Framework For Ethereum**
  
  T. Chen, **Z. Li**, Y. Zhang, X. Luo, A. Chen, K. Yang, B. Hu, T. Zhu, S. Deng, T. Hu, J. Chen, and X. Zhang

  *Proc. of the 39th IEEE International Conference on Distributed Computing Systems (ICDCS), Dallas, USA, July 2019.*

</ProjectCard>

<ProjectCard hideBorder=true>

  **GasChecker: Scalable Analysis for Discovering Gas-Inefficient Smart Contracts**
  
  T. Chen, Y. Feng, **Z. Li**, H. Zhou, X. Luo, X. Li, X. Xiao, J. Chen and X. Zhang

  *IEEE Transactions on Emerging Topics in Computing (TETC), 2020.*

</ProjectCard>

<ProjectCard hideBorder=true>

  **An Adaptive Gas Cost Mechanism for Ethereum to Defend Against Under-Priced DoS Attacks**
  
  T. Chen, X. Li, Y. Wang, J. Chen, **Z. Li**, X. Luo, M. Au, and X. Zhang

  *Proc. of 13th International Conference on Information Security Practice and Experience (ISPEC), pp. 3-24, Melbourne, Australia, December 2017. (**Best Paper Award**)*

</ProjectCard>

## Awards

- **Best Paper Nominee**, 13th International Symposium on Empirical Software Engineering and Measurement (ESEM), 2019.

- **Best Paper Award**, IEEE International Conference on Computer Communications (INFOCOM), 2018.

- **Best Paper on Blockchain**, China Computer Federation (CCF) Technical Committee on Block Chain, 2018.

- **Best Paper Award**, 13th International Conference on Information Security Practice and Experience (ISPEC), 2017.


<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
