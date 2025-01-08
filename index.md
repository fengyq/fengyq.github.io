---
layout: default
title: Home
---

<style>
    /* Responsive adjustments */
    .profile-section {
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        gap: 2rem;
        text-align: left;
    }
    .profile-text {
        flex: 2;
    }
    .profile-image {
        flex: 1;
    }
    .profile-image img {
        max-width: 100%;
        height: auto;
        border-radius: 5px;
    }

    /* Font size adjustments */
    h1 span {
        font-size: 1.5rem;
    }
    h2, h3, h4, h5, h6 {
        font-size: 1.2rem;
    }
    #recent-news {
        font-size: 1.2rem;
    }

    /* Content container */
    .content-wrapper {
        position: relative;
        padding-top: 0.5rem;
    }

    /* Responsive layout for mobile */
    @media (max-width: 768px) {
        .profile-section {
            flex-direction: column;
        }
        .profile-image {
            order: -1;
        }
    }
</style>

<div class="content-wrapper">
    <div class="lang-switch">
        <a href="/cn/">中文</a>
    </div>

    <h1><span style="color: #2c3e50; font-size: 1.5rem;">Yuanqing Feng (冯园庆)</span></h1>

    <div class="profile-section">
        <div class="profile-text">
            I am a <span style="color: #2c3e50; font-weight: 600;">Research Associate</span> at the <a href="https://www.med.upenn.edu/tishkoff/" target="_blank">University of Pennsylvania</a>. My research focuses on uncovering the <span style="color: #2c3e50; font-weight: 600;">genetic mechanisms underlying human evolution, phenotypic diversity, and disease susceptibility</span>, with particular emphasis on the role of <span style="color: #2c3e50; font-weight: 600;">non-coding variants</span> in human traits and diseases.

            With expertise in <span style="color: #2c3e50; font-weight: 600;">population genetics, functional genomics, and bioinformatics</span>, I have developed an integrative approach that utilizes cutting-edge technologies including <a href="https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-02856-6" target="_blank">MPRA</a>, <a href="https://www.nature.com/articles/s41576-023-00583-z" target="_blank">Hi-C</a>, and <a href="https://www.synthego.com/learn/crispr" target="_blank">CRISPR genome editing</a> to efficiently identify functional mutations and their target genes, contributing novel insights into the molecular mechanisms of human complex traits.

            Before joining UPenn, I received my PhD in Molecular Medicine from <a href="https://www.pku.edu.cn/" target="_blank">Peking University</a> (2017) and BS in Biology from <a href="https://www.jlu.edu.cn/" target="_blank">Jilin University</a> (2011).

            <div style="margin-top: 1.5rem;">
            <span style="color: #2c3e50; font-weight: 600;">Research Highlights:</span>
            <ul style="list-style-type: none; padding-left: 0; margin-top: 0.5rem;">
                <li style="margin-bottom: 0.5rem;">• Elucidating TRIM72's role in cardiac energy metabolism (<a href="https://pubmed.ncbi.nlm.nih.gov/33744959/" target="_blank">MBE</a>)</li>
                <li style="margin-bottom: 0.5rem;">• Identifying genetic variants and genes in skin pigmentation (<a href="https://pubmed.ncbi.nlm.nih.gov/38200130/" target="_blank">Nature Genetics</a>)</li>
                <li style="margin-bottom: 0.5rem;">• Understanding local adaptation in African populations (<a href="https://pubmed.ncbi.nlm.nih.gov/36868214/" target="_blank">Cell</a>)</li>
            </ul>
            </div>
        </div>
        <div class="profile-image">
            <img src="assets/images/photo1.jpg" alt="Yuanqing Feng">
        </div>
    </div>

    # <span id="recent-news">Recent News</span>
    {% include news_list.html limit=3 show_more=true %}
</div>