+++
title = "Microbiome transmission, probiotic prediction & cellular aging"
date = "2026-06-17T09:00:00+01:00"
draft = false
categories = ["Reading lists"]
tags = ["microbiome", "gut-microbiome", "microbiota", "bacteria", "health", "nutrition"]
series = ["Reading list"] 
ShowReadingTime = true
ShowPostNavLinks = true
showToc = true
TocOpen = true
+++

Not many entries today (just 6!), as times are busy with other things! Just a few new interesting papers that came to my attention on the human microbiome and some other population health studies.

## <span style="background-color: lightyellow;"><span style="font-size:22px">(a) Microbiome and population health</span></span>

{{< paper 
title="Strain transmission links human microbiomes along the oral-gut axis and across cohabiting individuals"
url="https://www.sciencedirect.com/science/article/pii/S3051383926000320?via%3Dihub" 
journal="Cell Press Blue, June 2026">}}
<b>Comment:</b> Another very interesting paper from the Segata lab in Italy, looking at microbiome transmission within households of cohabiting individuals. They find that cohabitation strongly predicts strain sharing, with an average sharing between cohabitants of 19% of gut strains and 26% of oral strains (compared to 6% gut and 0% oral sharing among non-cohabitants), with a highest value (44%) of oral sharing amongst romantic partners (unsurprisingly 😘). On that, they observed that oral strains appeared to be more dynamic/more transmissible than gut strains, and have a highest "replacement" rate. Oral-to-gut movement seemed to be observed and real, but quite selective which is an interesting observation. They found ~4% of species overlap between oral/fecal samples. Interestingly, when one strain was found at both sites in the same person, it was found in 3/4 of the cases, which supports the hypothesis of saliva-mediated oral-to-gut transmission, which is that abundant oral bacteria that are swallowed have more chances to survive the gut. Generally speaking though, they observed that when a species was found in both oral/gut of the same person, it was another strain, suggesting a body site-specific longer-term adaptation happening. Finally, these transmissible microbes weren't always "beneficial", with some associated with T2D and CRC biomarkers, suggesting that disease-associated microbes might also have traits allowing them to transmit more easily.
{{< /paper >}}

{{< paper 
title="Genome-scale metabolic modelling identifies vaginal microbiome members as potential probiotics"
url="https://www.nature.com/articles/s41564-026-02380-w" 
journal="Nature Microbiology, June 2026">}}
<b>Comment:</b> Very interesting applied microbiome research, in my opinion! Here, authors looked at 352 OTC probiotic products from US pharmacy websites. They found 36 unique "probiotic" species across 70 brands but no clear clustering of species composition by the proposed use by the manufacturer, such as gut vs vaginal health, reinforcing the point that the ["probiotics industry is selling us certainty it hasn't earned"](https://williamdepaolo.substack.com/p/the-microbiome-industry-is-selling) (yet). Authors go on to build a genome-scale metabolic mode from public genomes, called HaPaPro and which contains ~1k probiotics and other host-associated bacteria. They focus on vaginal health in this paper, and test 11 species found to inhibit (through their modelling) the _in vitro_ growth of _Gardnerella vaginalis_, a pathogen. 
{{< /paper >}}

{{< paper 
title="Identification of the complete pathway for conversion of bilirubin to urobilinogen by human gut bacteria"
url="https://www.biorxiv.org/content/10.64898/2026.06.10.731317v1.full" 
journal="bioRxiv, June 2026">}}
<b>Comment:</b> Bilirubin is a major product of mammalian heme catabolism and enters the intestine via the bile, after liver conjugation, and then can be metabolized by gut microbes through mechanisms that are largely unclear. In this preprint, authors ask which specific bacteria (and enzymes) convert bilirubin into urobilinogen. They identify enzymes BilR and BilV and characterise their activities, before screening for them in a broader collection of 1200 GTDB reference genomes encoding putative BilV. They identify _Collinsella_ genomes to have quite a lot of these genes.
{{< /paper >}}

## <span style="background-color: lightyellow;"><span style="font-size:22px">(d) Other pop health & other topics</span></span>

{{< paper 
title="Distinct metabolic signatures of Alzheimer's and Parkinson's disease revealed through genetic overlap"
url="https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(26)00136-2/fulltext" 
journal="eBioMedicine, May 2026">}}
<b>Comment:</b> Interesting paper on >300,000 people from UKB and Estonian Biobank using 249 of their circulating metabolites + proglucagon, along with summary statistics for AD, PD and cardiometabolic traits. Authors find that AD and PD have very different and distinct metabolic and genetic signatures, with AD being more liked to metabolic states influenced by BMI, T2D, CAD and stroke, while PD has very opposing patterns. Neurodegeneration, unsurprisingly, isn't a one-size-fits-all box and this works informs better on targeted metabolic approaches.
{{< /paper >}}

{{< paper 
title="Translating genome-wide association studies at multiple scales: Drug target prioritization, cellular architectures, and organ imaging"
url="https://www.cell.com/cell-genomics/fulltext/S2666-979X(26)00144-8" 
journal="Cell Genomics, June 2026">}}
<b>Comment:</b> Very interesting new review from the [Inouye Lab](https://mericlab.com/collaborations/) in Cambridge, summarizing how GWAS findings are being translated into biological/clinical insight at molecular, cellular and organ-levels scales. Among other things, it addresses how genetics can help for drug target reprioritisation. More generally, it argues that GWAS translation should not happen at one level only but after integrating genetics, molecular QTLs and proteomics, single-cell omics, imaging and MR/colocalisation/PRS.
{{< /paper >}}

{{< paper 
title="Plasma proteomic signatures of cellular aging predict human disease"
url="https://www.nature.com/articles/s41591-026-04446-y" 
journal="Nature Medicine, June 2026">}}
<b>Comment:</b> Very important study on aging, at the cellular level this time. Here authors looked at plasma proteomics from >60,000 individuals across 3 cohorts (GNPC incl. healthy + AD/PD/ALS, UKB participants with Olink plasma proteomics and follow-up, and NSHD 1946 birth cohort). They built those interesting cell type-specific aging models and looked at the "cell age gap" between cell-type age and expected age for someone of the same chronological age. They found that in healthy participants, there was a mix of people with no extreme cell age gaps, some with accelerated aging in 1 cell type and some with accelerated aging in >10 cell types. They linked lifestyle (smoking, obesity) and genetics (APOE) showing cell specific effects on aging. The strongest associations they found were for neurodegenerative diseases, especially ALS, linked to skeletal myocyte/cardiomyocyte aging. Alzheimer disease was strongly linked to astrocyte aging in UKB, and lung cancer also had links with alveolar cells aging. A lot to unpack, but cool study.
{{< /paper >}}