+++
title = "Reading list: Intestinal nutrition, microbiome GWAS, GLP-1 & AI stuff"
date = "2026-07-21T09:00:00+01:00"
draft = false
categories = ["Reading lists"]
tags = ["microbiome", "gut-microbiome", "microbiota", "bacteria", "health", "nutrition"]
series = ["Reading list"] 
ShowReadingTime = true
ShowPostNavLinks = true
showToc = true
TocOpen = true
+++

Some new articles in the reading list. I'll probably do a little break for those during the summer holidays. Have a good one!

## <span style="background-color: lightyellow;"><span style="font-size:22px">(a) Microbiome and population health</span></span>

{{< paper 
title="Genomic landscape of the human vaginal microbiome is linked to host genetics and population of origin"
url="https://www.nature.com/articles/s41588-026-02639-2" 
journal="Nature Genetics, June 2026">}}
<b>Comment:</b> Microbiome GWAS studies have historically started with the gut (and [we've been part of this effort here](https://www.nature.com/articles/s41588-021-00991-z), and [more recently here](https://www.nature.com/articles/s41588-026-02512-2)). Other body sites have been looked too, starting with the [oral microbiota](https://www.nature.com/articles/s41586-025-10037-7) last January. Here, authors present the first (metagenomics-based) vaginal microbiome GWAS study, but with much more than this, by also building a major genome catalog/resource (GVMG) of >65k genomes from public data (prokaryotic, eukaryotic and viral), which almost doubles the previous cataloguing efforts. They find that many vaginal microbes were missing from previous databases (and identify M. smithii as an archaeon there, which perhaps is worthy of some further study). They also refine the _Gardnerella/Bifidobacterium_ links by looking at how species cluster together. The vaginal virome is also better characterised, with some interesting phage-bacterial dynamics depending on health state. Regarding the host association part, 7 loci reach study-wide significance and replicate in >1 cohort, with the strongest signal being _OPRK1_ with _Ureaplasma urealyticum_. Other signals include: _ADAP1_ with _Lactobacillus mulieris_, _PRAMEF_-region with _B. piotii_, _MIR548AB_ with _Ezakiella coagulans_, _STON1–GTF2A1L/LHCGR/FSHR_ with _Prevotella sp000758925_, _MAN1A2P1/UQCRFS1_ with _B. swidsinskii_ and _CHIC2/PDGFRA_ with _Lactobacillus u861_. Very cool stuff!
{{< /paper >}}

{{< paper 
title="Common xenobiotics modulate gut microbial responses to low‑calorie sweeteners in vitro"
url="https://link.springer.com/article/10.1038/s44320-026-00225-6" 
journal="Molecular Systems Biology, June 2026">}}
<b>Comment:</b> For those of you who put artificial sweeteners in your coffee (nobody is perfect), this very interesting work looks at what happens when sweeteners meet the other xenobiotics we consume alongside them (here, advantame, caffeine, vanillin or duloxetine). In a large _in vitro_ screen, they found that isosteviol and duloxetine together were interacting to suppress selected gut bacteria, reduce diversity in a synthetic community (very cool passage experiment there), changed metabolite output (incl. lower SCFA/butyrate) and altered host cell responses. All _in vitro_ so far so no need to worry. Well, besides the nastiness of artificial sweeteners in general.
{{< /paper >}}

{{< paper 
title="Regional organization of nutrient absorption across the small intestine"
url="https://www.nature.com/articles/s41575-026-01225-5" 
journal="Nature Reviews Gastroenterology & Hepatology, July 2026">}}
<b>Comment:</b> Very interesting review on the spatial organisation of nutrient absorption in the small intestine (duodenum, jejunum, ileum until the ileocaecal valve) and how these function in different ways to absorb different nutrients in various "metabolic domains". Very good food for thoughts when thinking of the gut microbiota!
{{< /paper >}}

{{< paper 
title="Bifidobacterial genes upregulated by resistant starch investigated using multi-omics have orthologs in infant gut isolates "
url="https://academic.oup.com/ismecommun/article/6/1/ycag136/8680006?login=false" 
journal="ISME Communications, Jan 2026">}}
<b>Comment:</b> Interesting study including [some of our friends on this](https://thehalllab.com/), and a very "microbial systems-biology" mechanistic Bifidobacterium paper on resistant starch degradation. Authors highlight an interesting CAZyme CBM74-containing amylase cluster in Bifidobacterium globosum linked to high-amylose resistant starch. The link to infant B. pseudocatenulatum isolates is interesting when thinking about weaning, strain-level metabolism, and what starch-related CAZyme detections in metagenomes may actually mean.
{{< /paper >}}

{{< paper 
title="Applying Artificial Intelligence and machine learning in precision nutrition"
url="https://www.nature.com/articles/s41467-026-75004-w" 
journal="Nature Communications, July 2026">}}
<b>Comment:</b> Not entirely on the microbiota but very interesting Perspective on the topic of ML/AI and precision nutrition. Interesting discussion on how AI/ML should be selected, implemented, validated and reported for precision nutrition research, given the distinctive problems posed by dietary, microbiome, multi-omic, behavioural and longitudinal data. Authors suggest the **AI-PNUTRI checklist**, a practical framework that could be implemented to existing standards.
{{< /paper >}}

{{< paper 
title="Effects of probiotic supplementation on faecal short-chain fatty acid concentrations in healthy individuals: a systematic review and meta-analysis of randomized controlled trials"
url="https://link.springer.com/article/10.1186/s12937-026-01364-0" 
journal="Nutrition Journal, July 2026">}}
<b>Comment:</b> Do probiotics work? We hear this so much all the time as microbiome researchers and not many people can give a straight answer with confidence. Here, authors present a very interesting metaanalysis of RCTs testing whether probiotic supplementation actually does changes faecal SCFA concentrations in generally healthy people. For this work, the results are... negative! No statistically significant differences were detected in the faecal butyrate, acetate and propionate levels between individuals taking and not taking probiotics. I guess we'll have to stick to eating a lot of fibre then? :\) (More could probably be done, with more participants and not looking at fecal SCFA, but this is a start!)
{{< /paper >}}

## <span style="background-color: lightyellow;"><span style="font-size:22px">(b) Microbial genomics, ecology, evolution</span></span>

{{< paper 
title="AllTheBacteria: a community resource empowers biology and discovers novel peptide antibiotics"
url="https://www.biorxiv.org/content/10.1101/2024.03.08.584059v8" 
journal="bioRxiv, July 2026">}}
<b>Comment:</b> The preprint for a great resource led by the otherwise great [Zamin Iqbal at the University of Bath](https://zam-iqbal-lab.org/) along with many other talented collaborators. AllTheBacteria is _an open, community-built resource that transforms public bacterial short-read whole-genome sequencing reads into a uniformly processed discovery platform._ It gathers more than 2.4M bacterial/archaeal genomes from >11k species with all possible annotations you can think of. Really a great effort and I should use it more!
{{< /paper >}}

{{< paper 
title="The spread of sexually transmissible drug-resistant shigellosis in England: a genomic epidemiology study"
url="https://www.sciencedirect.com/science/article/pii/S1473309926002276" 
journal="The Lancet Infectious Diseases, July 2026">}}
<b>Comment:</b> Important genomic epidemiology paper on sexually-transmissible _Shigella sonnei_ infections in the UK (15 health regions) between 2004-2020. Authors found about a third of infections coming from MSM, another third from non-MSM and the rest from high-risk travel. The phylogenomic analysis showed that sexually transmitted _S. sonnei_ were spreading faster and more intensely than domestically acquired infections. They also observed a decline of azithromycin resistant in some isolates consistent with policy changes on treatments for gonorrhoea. Nicely done phylogenomic epidemiology paper.
{{< /paper >}}

{{< paper 
title="Glucagon-like peptide-1 receptor agonist prevents pulmonary fibrosis following acute COVID-19 infection associated with type 2 diabetes"
url="https://journals.asm.org/doi/full/10.1128/jvi.00401-26" 
journal="Journal of Virology, July 2026">}}
<b>Comment:</b> From the importance statement: _Some COVID-19 patients develop pulmonary post-acute sequelae of COVID-19 (PASC) with clinical symptoms lasting for years. Critically, the incidence of pulmonary PASC in PWT2D is four times higher than that in those without T2D._ GLP1 drugs are really found to be positively acting on a lot of things, either (most of the time) indirectly through weight-loss-related better health but more interestingly sometimes through more direct effects. Here, in this virology paper, authors show that GLP-1R agonist drugs directly acted on the pulmonary fibrosis symptoms that are typically seen in T2D patients after SARS-CoV-2 infection. Mechanisms are investigated in mice model.
{{< /paper >}}

## <span style="background-color: lightyellow;"><span style="font-size:22px">(c) Other pop health, AI & other topics</span></span>

{{< paper 
title="Analysis of 173,303 exomes and genomes in the Pakistan Genome Resource"
url="https://www.nature.com/articles/s41586-026-10667-5" 
journal="Nature, June 2026">}}
<b>Comment:</b> Impressive new resource adding onto the non-European reference genomic resources. Around 30% of coding variants found in this resource were absent even from all gnomAD, including South Asian samples there. Authors identify homozygous LoF variants in >6k genes (1/3rd of all protein-coding genes), with ~20% participants carrying at least one of these LoF gene variant. Very good example that under-represented populations can reveal biological findings that are missed by larger but less diverse other resources, and overall potentially improve genomic research representativity.
{{< /paper >}}

{{< paper 
title="The expanding landscape of GLP-1 medicines"
url="https://www.nature.com/articles/s41591-025-04124-5" 
journal="Nature Medicine, January 2026">}}
<b>Comment:</b> Already from last January, so potentially outdated when you see all the overwhelming advances made just in the first half of 2026 on additional treatments and new molecules targeting GLP1/GIPR going into clinical trials but still a very interesting review detailing the multiple reported benefits of these weight loss drugs already.
{{< /paper >}}

{{< paper 
title="Extreme heat and cause-specific risk of hospital admission in the adult population in England: a case time series analysis"
url="https://bmjopen.bmj.com/content/16/6/e105321" 
journal="BMJ Open, June 2026">}}
<b>Comment:</b> There is a heatwave in Europe as this paper is being published, which is an interesting coincidence. Here, authors look at heat-related risks for unscheduled hospital admissions. They analyse >4M records between 2008-2019 and find increases for a range of conditions like acute renal failure (Relative Risk of 1.37), metabolic disorders (1.28) and also marginally infectious and parasitic diseases (1.06), pneumonia (1.07) and COPD (1.08). Interestingly the associations were less clear and even negative for a range of cardiovascular outcomes. These events will only increase in frequency, this study helps to inform for a better planning.
{{< /paper >}}

{{< paper 
title="Whole-population trends in obesity across dimensions of inequality in England, 2019–25: a retrospective, longitudinal cohort study of 54 million adults"
url="https://www.thelancet.com/journals/landia/article/PIIS2213-8587(26)00120-8/fulltext" 
journal="The Lancet, June 2026">}}
<b>Comment:</b> Impressive retrospective longitudinal cohort of the whole population in England (n>54M individuals with NHS records), looking at trends in obesity across many variables, including age, sex, ethnicity, geography and SES factors. Obesity now affects ~1 in 3 adults in England (30.3% in April 2025, up from 26.3% before 2020). The fastest increases in new cases is observed in younger adults: +16% in 20–29yo and +19% in 30–39yo. People in the most deprived areas were 35% more likely to develop obesity than those in the least deprived. The gap was wider for women, and widest for Asian women, where the rate was nearly double. Finally, geographically, rates varied almost 6-fold across the country, and the steepest increases happened in the poorest areas (source: [one of the authors](https://www.linkedin.com/posts/spirosdenaxas_very-happy-to-share-our-new-paper-published-share-7475858659240103936-zuJn/?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAABG8__4BEOwvqpJgM7whzAREHJPP8OF4eNg)). Diagnoses earlier in life are quite worrying, given that obesity associates with increased risks of many other illnesses. 
{{< /paper >}}

{{< paper 
title="Citizen science platforms must mitigate against the threat of generative AI"
url="https://www.nature.com/articles/s41559-026-03141-y" 
journal="Nature Ecology & Evolution, July 2026">}}
<b>Comment:</b> Interesting and alarming letter highlighting the rise of AI-generated and AI-enhanced pictures on citizen science projects like eBird or any other wildlife resource, which obviously (duh) is of major impairment to identification, conservation and many other things.
{{< /paper >}}

{{< paper 
title="Rethinking bioinformatics expertise in the era of artificial intelligence"
url="https://www.nature.com/articles/s41746-026-02777-1" 
journal="npj Digital Medicine, May 2026">}}
<b>Comment:</b> A very interesting read for bioinformaticians who have been wondering about the value of their knowledge, expertise and skills with the tsunami wave of ever-so-competent LLM coding agents. Fear not, we will still need human brains to make good science. Sure, AI does accelerate technical execution but it will always remain very poor at designing studies scientifically decisively, curating data, validating and interpreting things in a biologically meaningful way.
{{< /paper >}}