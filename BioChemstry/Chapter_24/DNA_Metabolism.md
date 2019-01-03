# Chapter 24 DNA Metabolism
## Overview
-	DNA replication begins at specific origins, is semiconservative, bidirectional, and semidiscontinuous.
-	All DNA polymerases need a primer, extend the DNA chain in 5’->3’ direction (using dNTPs), and have 3’ to 5’ exonuclease activity for proofreading.
-	**DNA polymerase III** in E.*coli* and  DNA polymerase $\alpha$ and $\delta$ in eukaryotic cells are responsible for DNA replication *in vivo*.
-	DNA replisomes contain many protein components including helicases, single-stranded DNA binding proteins, topoisomerases, primases, ligases, etc.
-	It is likely that one DNA polymerase complex catalyzes the synthesis of both the leading and lagging strands at each replication fork via DNA looping.
-	Complex and redundant DNA repair systems have evolved to correct lesions in the DNA molecules.
## Basic Knowledgement
- Semiconservative
  - each strand acts as a template.
  - proved by experiment using E.*coli* cells. ([The experiment.](images/semi_exp.jpg))
  - daughter strands are synthesized **immediately** after parental strands separate. ([No complete unwinding DNA strands observed.](images/replication.jpg))
- DNA replication begins at **specific** sites and proceeds **bidirectionally**.
- The chemistry of DNA polymerizarion
  - revealed by *in vitro*(体外的) studies using DNA polymerase purified from E.*coli*
  - pol I(in E.*coli*) catalyze DNA polymerization *in vitro* in presence of a single strand DNA (**template**), a preexisting **primer** with a free 3'-OH group, and **dNTP**s.
  - [Elogation of DNA chain, using pol I. Pol I binds to DNA.](images/elongation.jpg)
  - The fundamental reaction: 3'-OH group of the growing strand attacks the 5'-$\alpha$-phosphorus of dNTPs. **So, the synthesized DNA is always extended in the 5'->3' direction.**
- DNA pol I
  - DNA polymerase I has three enzymatic activities in **a single polypeptide chain**, which can be cleaved into two functional parts by mild protease treatment:
    - smaller one: 5'->3' exonuclease activity.
    - larger one (aka. Klenow fragment): 3'->5' exonuclease activity and polymerase activity.
  - [**Proofreading**](images/proofread.jpg): The 3'->5' exonuclease activityoes is found to be able to remove mismatched base pairs, thus to proofread the newly incorporated nucleotides. And this activity is highly specific for mismatched base pairs.
  - [**Nick translation**](images/nickTranslation.jpg): The 5'->3' exonuclease activity allows pol I to degrade and replace an RNA or DNA strand paired to a DNA template simultaneously. Used in:
    - DNA repair
    - Removal of RNA primers in DNA replication
  - The velocity of this enzyme is low (600 necleotides/min), and its processivity (持续合成能力) is also low (about 50 nucleotides). So, E.*coli* cells don't use this for DNA replication.
- [DNA pol III](images/polIII.jpg)
  - Multimeric, containing at least 10 different subunits.
  - The holoenzyme exists as an asymmetric (不对称的) dimer, which is believed to be responsble for synthesizing the leading strand and the lagging strand.
  - Polymerization activity is on $\beta$ subunits.
  - Proofreading activity is on $\epsilon$ subunits.
  - $\beta$ subunits provide high processivity (more than 500,000 nucleotides per binding).
  - The rate of DNA synthesis is high (1,000 nucleotides pre second).
  - No 5'->3' exonuclease activity. So, it cannot remove the RNA primers.
  - Functions of each subunits: <br />
  
    | Subunit | Function |
    | :--: | :-- |
    | $\alpha$ | Polymerization |
    | $\epsilon$ | 3'->5' Proofreading exonuclease |
    | $\theta$ | Stabilization of $\epsilon$ subunit |
    | $\tau$ | Stable template binding; core enzyme dimerization |
    | $\gamma$ | Clamp loader |
    | $\delta$ | Clamp opener |
    | $\delta '$ | Clamp loader |
    | $\beta$ | DNA clamp required for optimal processivity |
    
  - The $\alpha, \beta$ and $\theta$ subunits are **core polymerase**.
  - The $\tau, \gamma, \delta$ and $\delta '$ subunits are called **Clamp-loading ($\gamma$) comlpex** that loads $\beta$ subunits on *lagging strand* at each Okazaki fragment.
- [Comparison of DNA polymerases of E.*coli*.](images/comparison&#32;of&#32;pols.jpg)
- Overview on DNA replication of E.*coli*:
  - **Helicase** (*dnaB*): moving along the DNA and separating the two DNA strands *using energy* from ATP;
  - **Topoisomerase** (拓扑异构酶): relieving topological strains in the helical structure (positive supercoils) generated during strand seperation;
  - **DNA-binding protein**: binding and stabilizing the single-stranded DNA generated;
  - **Primase** (*dnaG*): generating a short RNA primer;
  - **DNA polymerase III**: polymerizing and proofreading the nucleotides according to the templates;
  - **DNA polymerase I** (*pol A*): removing the RNA primers and replacing by a DNA sequence;
  - **DNA ligase**: sealing nicks between the Okazaki fragments.
- **Semidiscontinuous** synthesis of the two daughter DNA strands.
  - At a [replication fork](images/replicationFork.jpg), the overall elongation direction for one daughter strand is 5'->3' and 3'->5' due to the **antiparallel** features of DNA deplexes.
    - The 5'->3' (**leading strand**) is synthesized continuously.
    - The 3'->5' (**lagging strand**) is synthesized in small fragments (called *Okazaki fragments*). The fragments are then joined by **NDA ligase**s. The fragments are synthesized in 5'->3'.
- Replication origin is a 245 bp fragment in the E.*coli* DNA, called [*OriC*](images/OriC.jpg).
  - It contains three 13-mer with nearly identical sequences and fibe 9-mer repeats, all of which are highly conserved among all bacterial replication origins.
  - It also contains 11 **GATC** sequences, which can be methylated at the base ring of **A** (may be responsible for the only one replication per cell division).
  - Methylation of GATC sequences at *OriC* is believed to control the replication frequencies in E.*coli* cells.
    - Hemimethylated *OriC* was found to be unable to initiate another round of DNA replication.
    - It is believed that the hemimethylated **GATC** sequences at *OriC* is sequestered in the plasma membrane immediately after one round of DNA replication, thus blocking another round of replication until the **GATC** sequences are released and fully methylated by **Dam methylase.**
    - [The delay of methylation is hypothesized to limit DNA replication to occur once per cell division.](images/hemomethyl.jpg)
    - The slow hydrolysis of ATP by **DnaA** protein was also proposed to regulate replication initiation.
## Replication
### In E.*coli*
- [**Initiation** stage](images/initiation_stage.jpg)
  - 8 **DnaA** protein molucules (with ATP bound) bind to the five 9 bp repeats at *OriC* that is supercoiled.
  - **HU** (a histone-like protein) binds to DnaA complex and opens the DNA strands at the AT-rich 13-mer repeats.
  - **DnaB**, the helicase, binds (aided by **DnaC** protein) to the opened DNA strands as two hexamer clamps and further opens (unwinds) the strands in both directions, thus forming the prepriming complex.
  - Other proteins are listed in this [chart](images/initiation_proteins.png), which are also important.
- **Elongation** stage
  - Further unwinding of the DNA duplex needs DNA gyrase (a topoisomerase II) to relieve the supercoils ahead the replication forks and SSB (single-stranded DNA-binding protein) for stabilizing the unwound single-stranded DNAs.
  - The **primase** (a RNA polymerase), recruited to the open templates via DnaB, was found to be the enzyme that catalyzes the synthesis of the RNA primers.
  - For the [leading strand](images/leading.jpg), *only one* primer is synthesized, which is then elongated by **DNA polymerase III** in a continuous way.
  - On the [lagging strand](images/lagging.jpg), **DnaB** (the helicase) intermittently recruits **DnaG** (the primase) to form a complex called **primosome**, and *repeatedly* making primers for the Okazaki fragments. Each Okazaki fragment is then synthesized on one RNA primer by **DNA polymerase III**.
  - The RNA primers are removed and replaced by a DNA sequence in a reaction catalyzed by **DNA polymerase I**, using its nick translation activity (5’->3’ exonuclease + polymerase).
  - The final Okazaki fragments are joined together by the **DNA ligase**.
    - **DNA ligase** catalyzes the formation of a phosphodiester bond between a 3’-OH group and a 5’ phosphate group of two DNA strands, where the 5’ phosphate is first activated by being modified by an AMP group coming from NAD+ (the bacterial enzyme) or ATP (the virus and animal enzymes).
  - [DNA polymerase I replaces the RNA primers by DNA sequences and DNA ligase seals the nicks.](images/ligase.jpg)
  - The leading and lagging strands are believed to be synthesized *coordinately* by a single asymmetric **DNA polymerase III dimer**.
    - The two polymerase III cores (having the $\alpha\epsilon\theta$ subunits) are believed to be connected by two $\tau$ subunits.
    - The coupling is believed to be accomplished via *looping* of the lagging strand template.
    - [The DNA polymerase III clamp loader](images/clamp_loader.jpg)
    - DNA synthesis on the leading and lagging strands
      - [Step 1](images/part1.jpg)
      - [Step 2](images/part2.jpg)
      - [Step 3](images/part3.jpg)
      - [Step 4](images/part4.jpg)
    - [The proteins needed at the E.*coli* Replication Fork](images/elongation_proteins.jpg)
- **Termination** stage
  - E.*coli* DNA replication ends at a specific terminus region with multiple copies of a 20 bp *Ter* sequence.
    - The *Ter* sequences are positioned in two clusters with opposite orientations.
    - The **Tus** (terminus utilization substance) protein can bind to the *Ter* sequences.
    - At each round of DNA replication, only one Tus-*Ter* complex seems to function to arrest a replication fork from one direction.
    - The opposing replication forks generally halt when they collide.
    - The *Ter* sequences do **not** seem to be essential for stopping replication.
    - [The *Ter* sequences are positioned on the chromosome in two clusters with opposite orientations.](images/ter.jpg)
  - [The two newly synthesized circular chromosomal DNAs are topologically interlinked (catenated) and is finally separated by the action of a **Type II topoisomerases**.](images/seperate.jpg)
### In eukaryotic cells (yeast)
-	Formation of the RNA primers and the initial incorporation of deoxynucleotides are believed to be catalyzed by **DNA polymerase $\alpha$** (which has no proofreading activity).
-	Later chain extension is believed to be catalyzed by **DNA polymerase $\delta$**, which has proofreading activity.
-	Specific sequences (~150 bp) that can function as replication origins have only been identified in yeast (called autonomously replicating sequences, or **ARS**).
-	The rate of DNA synthesis in eukaryotic cells is about one twentieth of that of the E.*coli* cells.
-	Replication in the eukaryotic genomes begins at **many** replication origins.
- Termination of replication on linear eukaryotic chromosomes involves the synthesis of special structures called **telomeres (端粒)** at the ends of the chromosomes.
-	**ORC**: origin recognition complex, is required for initiation. **ORC** interacts with and is regulated by a number of proteins involved in the control of cell cycle.
-	**Pol $\alpha$/primase**: synthesizes the RNA primers and a stretch of DNA sequences, has no proofreading activity.
-	**Pol $\delta$**: replaces **Pol $\alpha$/primase** to further extend the RNA-DNA strand, has proofreading activity.
-	**PCNA** (proliferating cell nuclear antigen): a trimeric ring-shaped protein that clamps **Pol $\delta$** onto the DNA template.
-	**RFC** (replication factor C): a clamp loader for **PCNA**.
-	**Topoisomerases**: relieves the torsional strain induced by the growing replication fork.
-	**Ligases**: joins the Okazaki fragments (much shorter than those in E.*coli* cells), as well as the leading strand.
## Degration
- DNA is degraded by nucleases (DNases)
  - **Exonucleases (外切酶)** degrade nucleic acids from one end of the molecule. Operate in only 5'->3' **or** 3'->5' direction, removing nucleotides **only** from the 5' or 3' end.
  - **Endonucleases (内切酶)** can begin to degrade at any sites in a nucleic acid strand or molecule. Reduce it to smaller and smaller fragments.
## Repiration
DNA Repair: maintaining the integrity of the genomic DNA is essential to all cells.
- The DNA molecules can become damaged via a variety of internal (e.g., autonomous deamination of bases) or external (e.g., exposure to UV light and chemical agents) processes.
- Most carcinogens are found to be strong mutagens: the [Bruce Ames Test](images/ame&#32;test.png) has been used to examine whether a chemical is a potential human carcinogen by testing its mutagenicity on certain bacterial strains.
- A diversity of repair systems have evolved : **mismatch repair**, **base-excision repair**, **nucleotide-excision repair** and **direct repair** are the common types found. [Chart 1](images/repair1.jpg) [Chart 2](images/repair2.jpg).
-	Many DNA repair systems are energetically expensive (very inefficient compared with other metabolic pathways) and redundant (especially to some common types of lesions).
-	Complementary synthesis (based on the duplex DNA structure) after elimination of the damaged nucleotides is a common principle for all the repair systems (The methyled strand is the correct one).
-	When the DNA strands are extensively damaged, the SOS response and error-prone repair (or translesion replication, being a desperate strategy) will occur.
-	Some proteins may act to repair lesions (the ABC excinuclease, RecA, Pol II), some to inhibit cell divisions (e.g., sulA), and others to act in translesion replication (Rec A protein, SSB, DNA polymerase V made of UmuC and the shortened UmuD or DNA polymerase IV encoded by the dinB gene).
-	**Random nucleotides may be added in place of the damaged ones during translesion replications**, but the detailed mechanism has not been revealed.
-	The increased mutations may generate a few cells (although almost all dead) that are better fit to survive the catastrophic conditions (better species may thus evolve).