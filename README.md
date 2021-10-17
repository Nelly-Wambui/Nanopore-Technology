# Nanopore Sequencing Technology
## INTRODUCTION TO THE DNA SEQUENCING TECHNOLOGIES

The Human Genome Project set out to determine all the 3 billion nucleotides
in the human genome.

There have been some generations of techniques over the years that have made it possible to improve 
the sequencing of DNA.

Initially, the methods used in sequencing of proteins could not be applied in sequencing of DNA 
because DNA was longer and were made of fewer yet similar units making it really difficult to
distinguish between the units. RNA sequencing preceded DNA sequencing as they were not complicated by
having complimentary strands and were much shorter. At first only the nucleotide composition of RNA
could be measured, and as time went by a technique based on the detection of radiolabelled 
partial-digestion fragments after two-dimensional fractionation was made use of. it made it possible to
produce  the first complete protein-coding gene sequence in 1972, that of the coat protein of 
bacteriophage MS2. Ray Wu and Dale Kaiser used DNA polymerase to fill the ends in with radioactive nucleotides,
and before too long, this principle was generalized through the use of specific oligonucleotides to prime the DNA polymerase.
The 2D-fractionation method, which invoved use of electrophoresis and chromatography was faced out by use of a single 
separation by polynucleotide length via electrophoresis through polyacrylamide gels, which provided much greater resolving power. 
The plus and minus method by Alan Coulson and Sanger and the chemical cleavage technique by Allan Maxam and Walter Gilbert made use of 
the polyacrylamide gel technique. 

## FIRST GENERATION OF DNA SEQUENCING 

Maxam-Gilbert sequencing (chemical sequencing) and Sanger chain termination sequencing, represent the first generation 
of DNA sequencing technology. The chemical cleavage technique was the first to be widely adopted. Due to the complexity of the method and 
the harsh chemicals required for the reaction, Sanger sequencing ultimately surpassed Maxam-Gilbert sequencing in popularity. 
Sanger's chain termination or the dideoxy technique made use of chemical analogues of the deoxyribonucleotides (dNTPs) that are the 
monomers of DNA strands. Dideoxynucleotides (ddNTPs) lack the 3′ hydroxyl group that is required for extension of DNA chains,
and therefore cannot form a bond with the 5′ phosphate of the next dNTP. Mixing radiolabelled ddNTPs into a DNA extension reaction 
at a fraction of the concentration of standard dNTPs results in DNA strands of each possible length being produced, as the 
dideoxynucleotides get randomly incorporated as the strand extends, halting further progression.

By performing four parallel reactions containing each individual ddNTP base and running the results on four lanes of a polyacrylamide gel, 
one is able to use autoradiography to infer what the nucleotide sequence in the original template was, as there will be a radioactive band 
in the corresponding lane at that position of the gel. 

Improvements such as use of one vessel instead of four by replacing phospho- or tritrium-radiolabelling with fluorometric based detection and 
the use of capillary based electrophoresis which replaced gel-based electrophoresis, contributed to the development of 
highly automated DNA sequencing machines. Applied Biosciences launched the first commercial DNA sequencer in 1986.


![MAXAM AND GILBERT PROCEDURE](https://geneticeducation.co.in/wp-content/uploads/2019/01/seq-DNA.007-e1547224449460.jpeg)

                                                                                          MAXAM AND GILBERT PROCEDURE



![SANGER PROCEDURE](https://onlinesciencenotes.com/wp-content/uploads/2021/05/procedure-of-Sangers-sequencing.jpg)

                                                                                          SANGER CHAIN TERMINATION PROCEDURE




![ABI 3730](https://image.slidesharecdn.com/sangersequencing1990vs2017-infograph-170620074206/95/sanger-sequencing1990-vs-2017-infograph-1-638.jpg?cb=1497944672)

                                                                                          ABI 3730
                                                                                          
                                                                                          
## SECOND GENERATION OF DNA SEQUENCING    

The second generation of DNA sequencing replaced radio- or fluorescently-labelled dNTPs or oligonucleotides before visualising with electrophoresis 
with a luminescent method for measuring pyrophosphate synthesis which consisted of a two-enzyme process in which ATP sulfurylase is used to convert
pyrophosphate into ATP, which is then used as the substrate for luciferase, thus producing light proportional to the amount of pyrophosphate.
In this method, the DNA sequence was infered by measuring pyrophosphate production as each nucleotide is washed through the system in 
turn over the template DNA affixed to a solid phase. Both Sanger and pyrosequencing methods made use of the direct action of DNA polymerase.
The pyrosequencing method was better in that; it could be performed using natural nucleotides instead of the heavily-modified dNTPs used 
in the chain-termination protocols, and observed in real time instead of requiring lengthy electrophoreses. 

### 1. ROCHE 454 SEQUENCING

Pyrosequencing was lincensed to 454 Life Sciences and later purchased by Roche. They allowed the mass parallelisation of sequencing reactions, greatly increasing the amount 
of DNA that can be sequenced in any one run. Libraries of DNA molecules are first attached to beads via adapter sequences, which then undergo a water-in-oil emulsion PCR (emPCR) to coateach bead in a clonal DNA population, where ideally on average one DNA molecule ends up on one bead, which amplifies in its own droplet in 
the emulsion. These DNA-coated beads are then washed over a picoliter reaction plate that fits one bead per well; pyrosequencing then occurs 
as smaller bead-linked enzymes and dNTPs are washed over the plate, and pyrophosphate release is measured using a charged couple device (CCD) 
sensor beneath the wells. This set up was capable of producing reads around 400–500 base pairs long, for the million or so wells that would be 
expected to contain suitably clonally-coated beads. Parallelisation increased the yield of sequencing efforts by orders of magnitudes, for 
instance allowing researchers to completely sequence a single human's genome.
Parallel sequencing techniques developed after the success of 454 such as the Solexa method of sequencing which was later purchased by Illumina.

![ROCHE 454 SEQUENCING TECHNIQUE](https://slideplayer.com/slide/4053956/13/images/14/Roche+454+Sequencing+Metzker%2C+NG+2010.jpg)

                                                                                           ROCHE 454 SEQUENCING TECHNIQUE

### 2. ILLUMINA (SOLEXA) SEQUENCING

It adopted the technology of sequencing by synthesis using removable fluorescently labeled chain-terminating nucleotides that are able to produce 
a larger output at lower reagent cost. The clonally enriched template DNA for sequencing is generated by PCR bridge amplification, also known as 
cluster generation, into miniaturized colonies called polonies. The output of sequencing data per run is higher (600 Gb), the read lengths are shorter 
(approximately 100 bp), the cost is cheaper, and the run times are much longer (3-10 days) than most other systems. Illumina provides six industrial-level
sequencing machines (NextSeq 500, HiSeq series 2500, 3000, and 4000, and HiSeq X series five and ten) with mid to high output (120–1500 Gb) as well as 
a compact laboratory sequencer called the MiSeq, which, although small in size, has an output of 0.3 to 15 Gb and fast turnover rates suitable for 
targeted sequencing for clinical and small laboratory applications. The MiSeq uses the same sequencing and polony technology such as the high-end 
machines, but it can provide sequencing results in 1 to 2 days at much reduced cost. Illumina’s new method of synthetic long reads using TruSeq technology
apparently improves de novo assembly and resolves complex, highly repetitive transposable elements. 

![ILLUMINA SEQUENCING TECHNIQUE](https://www.intechopen.com/media/chapter/49419/media/image2.png)

                                                                                            ILLUMINA SEQUENCING TECHNIQUE

### 3. Sequecing by Oligonucleotide Ligation and Detection (SOLiD)

This is the third option in the second generation of DNA sequencing techniques and as the name suggests, SOLiD sequenced not by synthesis,
but by ligation using DNA ligase. The instrument was marketed by Life Technologies and first released in 2008 by Applied Biosystems Instruments (ABI).

DNA is first fragmented either enzymatically or by sonication (excitation using ultrasound) to create smaller strands. Adaptors (short, 
double-stranded pieces of synthetic DNA) are then ligated to these fragments with the help of DNA ligase, an enzyme that joins DNA strands. 
The adaptors enable the sequence to become bound to a complementary counterpart.

Adaptors are synthesised so that one end is 'sticky' whilst the other is 'blunt' (non-cohesive) with the view to joining the blunt end to the blunt 
ended DNA. This could lead to the potential problem of base pairing between molecules and therefore dimer formation. To prevent this, the chemical
structure of DNA is utilised, since ligation takes place between the 3'-OH and 5'-P ends. By removing the phosphate from the sticky end of the 
adaptor and therefore creating a 5'-OH end instead, the DNA ligase is unable to form a bridge between the two termini.

![SOLiD SEQUENCING TECHNIQUE](https://atdbio.com/_next/image?url=%2Fassets%2Fbook%2Fngs-library-preparation.svg&w=640&q=75)

                                                                                             SOLid SEQUENCING TECHNIQUE
                                                                                             
### 4. DNA NANOBALL SEQUENCING

Complete Genomics developed DNA nanoball sequencing (DNBS) as a hybrid of sequencing by hybridization and ligation.
Small fragments (440–500 bp) of genomic DNA or cDNA are amplified into DNA nanoballs by rolling-circle replication that requires the 
construction of complete circular templates before the generation of nanoballs. The DNA nanoballs are deposited onto an arrayed flow cell, 
with one nanoball per well sequenced at high density. Up to 10 bases of the template are read in 5′ and 3′ direction from each adapter. 
Since only short sequences, adjacent to adapters, are read, this sequencing format resembles a multiplexed form of mate-pair sequencing 
similar to using Exact Call Chemistry in SOLiD sequencing. Ligated sequencing probes are removed, and a new pool of probes is added, 
specific for different interrogated positions. The cycle of annealing, ligation, washing, and image recording is repeated for all 10 positions
adjacent to one terminus of one adapter. This process is repeated for all seven remaining adapter termini. 
The major disadvantage of DNBS is the short length of reads and the length of time for the sequencing projects.
The major advantage of this approach is the high density of arrays and therefore the high number of DNBs (~350 million) that can be sequenced.
In 2015, the Chinese genomics service company BGI-Shenzhen acquired Complete Genomics and introduced the Retrovolocity system for large-scale, 
high-quality whole-genome and whole-exome sequencing with 50x coverage per genome and with the sample to assembled genome produced in less than 8 days.

![DNA NANOBALL SEQUENCING](https://media.springernature.com/original/springer-static/image/chp%3A10.1007%2F978-1-4939-6622-6_1/MediaObjects/316167_2_En_1_Fig9_HTML.gif)

                                                                                              DNA NANOBALLSEQUENCING
                                                                                              
### 5. ION TORRENT

Ion Torrent, another Life Technologies product, is the first so-called ‘post-light sequencing’ technology and the last remarkable second-generation 
sequencing platform . It uses neither fluorescencenor luminescence. In a manner analogous to 454 sequencing, beads bearing clonal populations of DNA fragments, 
produced via an emPCR are washed over a picowell plate, followed by each nucleotide in turn; however nucleotide incorporation is measured not by pyrophosphate release,
but the difference in pH caused by the release of protons (H + ions) during polymerisation. 
The sequencing reaction is performed within a microchip that is amalgamated with flow cells and electronic sensors at the bottom of each cell. 
The incorporated nucleotide is converted to an electronic signal detected by the electronic sensors. This technology allows for very rapid 
sequencing during the actual detection phase. As with 454, and all other pyrosequencing technologies, it is less able to readily interpret 
homopolymer sequences due to the loss of signal as multiple matching dNTPs incorporate.
There are four sequencing chips to choose from. The Ion PI Chip is used with the Proton sequencer, and the Ion 314, 316, or 318 Chips are used 
with the Ion PGM. The Ion 314 Chip provides the lowest reads at 0.5 million reads per chip, whereas the Ion 318 Chip provides the highest reads 
of up to 5.5 million reads per chip. The Proton sequencer provides a higher throughput (10–100 Gb vs. 20 Mb–1 Gb) and more reads per run (660 Mb vs. 11 Mb)
than the PGM chips, but the read lengths (200–500 bp), run time (4–5 h), and accuracy (99%) are similar.

![ION TORRENT SEQUENCING](https://www.researchgate.net/publication/243969229/figure/fig1/AS:340876061626368@1458282594524/Ion-sequencing-work-flow-The-overall-workflow-is-shown-in-a-A-genome-library-is.png)


                                                                                                ION TORRENT SEQUENCING
                                                                                                
## THIRD GENERATION DNA SEQUENCING

This generation involves the emergence of single-molecule sequencing.

The first single-molecule sequencing technology was developed in the lab of Stephen Quake, later commercialized by Helicos BioSciences, 
and worked in the same manner that Illumina does, but without any bridge amplification. DNA templates become attached to a planar surface, 
and then propriety fluorescent reversible terminator dNTPs (so-called ‘virtual terminators’) are washed over one base a time and imaged,
before cleavage and cycling the next base over. While relatively slow and expensive, and producing relatively short reads, this was the first 
technology to allow sequencing of non-amplified DNA, thus avoiding all associated biases and errors. As Helicos filed for bankruptcy early in 2012, 
other companies took up the third-generation baton.

### 1. Single-molecule real-time (SMRT) sequencing by pacific biosciences

The RS II sequencer and single molecule real time (SMRT) platform is from Pacific Biosciences. SMRT sequencing is performed in SMRT cells 
that contain 150,000 ultra-microwells at a zeptoliter scale where one molecule of DNA polymerase is immobilized at the bottom of each well 
using the biotin-streptavidin system in nanostructures known as zero-mode waveguides (ZMWs). These ZMWs exploit the properties of light passing 
through apertures of a diameter smaller than its wavelength, which causes it to decay exponentially, exclusively illuminating the very bottom of 
the wells. This allows visualisation of single fluorophore molecules close to the bottom of the ZMW, due to the zone of laser excitation being so 
small, even over the background of neighbouring molecules in solution. Deposition of single DNA polymerase molecules inside the ZMWs places them 
inside the illuminated region. By washing over the DNA library of interest and fluorescent dNTPs, the extension of DNA chains by single nucleotides
can be monitored in real time, as fluorescent nucleotide being incorporated – and only those nucleotides – will provide detectable fluorescence, 
after which the dye is cleaved away, ending the signal for that position. Since all four nucleotides are added simultaneously and measured in real time, 
the speed of sequencing is much increased compared to technologies where individual nucleotides are flushed sequentially. Although the reported accuracy 
was 99.3% initially with read lengths of about 900 bp, circularizing the template and sequencing it several times using a technology called SMRTbell 
templates provided longer reads and improved the accuracy to >99.999%. Once sequencing is initiated, the system’s computational Blade Center performs 
real-time signal processing, base calling, and quality assessment. Primary analysis data, including trace and pulse data, read-length, distribution, 
polymerase speed, and quality measurement, is streamed directly to the secondary analysis software called SMRT Analysis that is capable of processing 
sequencing data in real time. 

![SMRT PACBIO SEQUENCING](https://www.pacb.com/wp-content/uploads/Infographic_SMRT-Sequencing-How-it-Works.png)

                                                                                                SMRT PACBIO SEQUENCING
                                                                                                
### 2. NANOPORE SEQUENCING

The latest single-molecule sequencing system is from Oxford Nanopore Technologies. The MinION Mkl is a portable handheld device for DNA
and RNA sequencing that attaches directly to a laptop/computer using a USB port, whereas the PromethION is a small bench-top system. 
In this sequencing technology, the first strand of a DNA molecule is linked by a hairpin to its complementary strand. The DNA fragment is
passed through a protein nanopore (a nanopore is a nanoscale hole made of proteins or synthetic materials. When the DNA
fragment is translated through the pore by the action of a motor protein attached to the pore, it generates a variation of an ionic current
caused by differences in the moving nucleotides occupying the pore. This variation of ionic current is recorded progressively
on a graphic model and then interpreted to identify the sequence. The sequencing is made on the direct strand generating
the “template read” and then the hairpin structure is read followed by the inverse strand generating the “complement read”, these reads is
called "1D". If the “template” and “complement” reads are combined, then we have a resulting consensus sequence called “two direction
read” or "2D".

![NANOPORE SEQUENCING](https://www.economist.com/img/b/608/818/90/sites/default/files/images/print-edition/20211002_STC967.png)

                                                                                                NANOPORE SEQUENCING
                                                                                                
REFERENCES:
1. James M.Heather, BenjaminChain. The sequence of sequencers: The history of sequencing DNA. Genomics
Volume 107, Issue 1, January 2016, Pages 1-8. https://doi.org/10.1016/j.ygeno.2015.11.003
2. Mehdi Kchouk1,3*, Jean-François Gibrat2 and Mourad Elloumi3. Generations of Sequencing Technologies: 
From First to Next Generation. Kchouk et al., Biol Med (Aligarh) 2017, 9:3 
3. Alberto Magi, Roberto Semeraro, Alessandra Mingrino, Betti Giusti, Romina D’Aurizio. Nanopore sequencing data analysis: 
state of the art, applications and challenges. Briefings in Bioinformatics, Volume 19, Issue 6, November 2018, Pages 1256-1272
