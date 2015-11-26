# FecalSeq enrichment protocol

Portions of this protocol are modified from the NEBNext Microbiome DNA Enrichment Kit manual (New England Biolabs cat. #E2612S)

**Materials and reagents**

* Extracted fecal-derived DNA of known quantity
* NEBNext Microbiome DNA Enrichment Kit (New England Biolabs; catalog number E2612S or E2612L)
* Rotating mixer
* Magnetic rack for 1.5/2.0 ml microcentrifuge tubes
* 5 M NaCl

## Before beginning

1. Extract and prepare DNA samples

	While any fecal DNA (fDNA) extraction method should in principle be compatible with the MBD enrichment, methods that maximize the recovery of host DNA are preferable. Bead-beating methods that increase total DNA yield from feces, for example, should be avoided because the mechanical disruption increases the yield of cell-wall-bound DNA (i.e., from bacteria or plants) while fragmenting host DNA.

	We suggest aiming for a total yield of 1 µg of DNA for all samples in a maximum volume of 30 µl each, although we have had success with as little as 500 ng (the yield of host DNA is likely more important than the yield of total fDNA). If the volume is greater than 30 µl, the DNA can be concentrated via a bead cleanup (Auxiliary protocol A).
	
	Prior to enrichment, DNA should be quantified for the total yield (e.g., by fluorometer or spectrophotometer). Ideally, the host DNA should also be quantified by qPCR (Auxiliary protocol B).

2. Calculate the required volume of MBD2-Fc-bound magnetic beads (hereafter referred to as "MBD beads") for each enrichment reaction, as well as the total volume for a set of reactions as follows.

	As an approximate rule, prepare 1 µl of MBD beads for every 6.25 ng of target host DNA in each enrichment reaction. If samples contain less than 6.25 ng of host DNA or if the amount of host DNA is not quantified, prepare 1 µl of MBD beads.
	
	We recommend preparing batches of MBD beads (see step 5) with a minimum volume of 40 µl, as lower volumes preclude adequate mixing. If a smaller volume is needed, leftover unused MBD beads can be stored at 4°C for up to a week.

3. Resuspend protein A magnetic beads by gently pipetting the mixture up and down until the suspension is homogenous, or by slowly rotating the mixture at 4°C for 15 minutes. **Do not vortex**.

4. Prepare 1x bind/wash buffer by diluting 1 part 5x bind/wash buffer with 4 parts DNase-free water. As a general rule, the volume of 1x bind/wash buffer needed can be calculated as:

	2.5 ml + 1.2 ml x [number of enrichment reactions]
	
	The amount of 1x bind/wash buffer depends on the total volume of MBD beads and the total number of enrichment reactions. MBD beads can be prepared with a maximum volume of 160 µl in a single reaction. As very small volumes (1-8 µl) of beads are needed for our enrichment method, a single bead preparation reaction is nearly always sufficient. If more beads are needed, increase the number of bead preparation reactions and adjust the volume of 1x bind/wash buffer accordingly. Alternatively, for volumes up to 320 µl, prepare an additional 1 ml of 1x bind/wash buffer per bead preparation reaction and add an extra wash step (see step 14).

	2.5 ml of 1x bind/wash buffer are required for a single bead preparation reaction up to 160 µl. Prepare an additional 1.2 ml of 1x bind/wash buffer per enrichment reaction. This number takes into account the volume needed to prepare 2 M NaCl elution buffer in the following step.

	Keep 1x bind/wash buffer on ice throughout the MBD bead preparation. For the wash steps following the capture reaction, 1x bind/wash buffer can be at room temperature.

5. Prepare 2 M NaCl elution buffer by diluting 5 M NaCl with 1x bind/wash buffer. 100 µl of 2 M NaCl elution buffer are needed per enrichment reaction.

	1x bind/wash buffer has a NaCl concentration of 150 mM. 1 ml of 2M NaCl elution buffer can be prepared by adding 370 µl of 5 M NaCl with 630 µl of 1x bind/wash buffer.

## Preparing MBD beads

6. If preparing 40 µl of MBD beads, add 4 µl of MBD2-Fc protein to 40 µl of protein A magnetic beads in a 1.5 ml microcentrifuge tube. For preparing other volumes (*n* µl) of MBD beads, add *n*/10 µl MBD2-Fc protein to *n* µl of protein A magnetic beads. 

	As a rule, we do not prepare less than 40 µl of MBD beads due to diminished efficiency of both rotational mixing and magnetic separation at low volumes.

7. Mix the bead-protein mixture by rotating the tube in a rotating mixer for 10 minutes at room temperature.

8. Briefly spin the tube and place on the magnetic rack for 2-5 minutes until the beads have collected to the wall of the tube and the solution is clear.

9. Carefully remove and discard the supernatant with a pipette without disturbing the beads.

10. Add 1 ml of 1x bind/wash buffer (kept on ice) to the tube to wash the beads. Pipette up and down a few times to mix.

11. Mix the beads by rotating the tube in a rotating mixer for 3 minutes at room temperature.

12. Briefly spin the tube and place on the magnetic rack for 2-5 minutes until the beads have collected to the wall of the tube and the solution is clear.

13. Carefully remove and discard the supernatant with a pipette without disturbing the beads.

14. Repeat steps 10-13.

	If preparing between 160 µl and 320 µl of beads, repeat steps 10-13 twice for a total of three washes to ensure the removal of unbound MBD2-Fc protein.

15. Remove the tube from the rack and add *n* µl (determined in step 6) of 1x bind/wash buffer to resuspend the beads. Mix by pipetting the mixture up and down until the suspension is homogenous.

## Capture methylated host DNA

Since reaction volumes are well under 100 µl, multiple enrichment reactions can be processed together in a microplate, with pipetting steps conducted using a multichannel pipettor. Compatible rotating mixers and magnetic separators would also be required. Here, we proceed to describe the capture procedure using a 1.5 ml tube.

The total volume of the capture reaction is an important consideration. We have observed decreased DNA binding efficiency when the concentration of MBD beads or DNA in the capture reaction is low. We therefore recommend maintaining a total reaction volume of approximately 40 µl, as we have experienced consistent success with this volume even when adding as little as 1 µl of MBD beads. Decreasing the reaction volume may result in decreased efficacy of rotational mixing. It is a good idea to keep the volume of all reactions consistent as this facilitates processing of many samples and, if DNA amounts and bead volumes are kept consistent, serves as a control for the effects of bead or DNA concentration on enrichment efficiency. Our subsequent procedures assume a reaction volume of 40 µl (not including MBD beads). If using other reaction volumes, pay particular attention to notes following each step in this section.

16. Aliquot 8 µl of 5x bind/wash buffer to a 1.5 µl microcentrifuge tube

	For reaction volumes other than 40 µl, tune the volume of 5x bind/wash buffer to maintain 1x concentration and adjust accordingly the volume of DNase-free water added in step 17. The volume of MBD beads should be excluded from this calculation as prepared MBD beads are already at 1x concentration.

	We recommend equilibrating 5x bind/wash buffer to room temperature prior to aliquoting for more accurate pipetting. 

17. Add up to 30 µl of DNA (prepared in step 1) to the tube. Bring the total volume to 40 µl with DNase-free water.

	For reaction volumes other than 40 µl, adjust the volume of DNase-free water added to reach the target volume. Be sure to maintain 1x bind/wash concentration.

18. Add MBD beads to the tube using the volume determined in step 2. Pipette the mixture up and down or swirl a few times to mix.

	As an approximate rule and as stated above, add 1 µl of MBD beads for every 6.25 ng of target host DNA in each enrichment reaction. If samples contain less than 6.25 ng of host DNA or if the amount of host DNA is not quantified, add 1 µl of MBD beads.

19. Incubate the reaction for 15 minutes at room temperature with rotation.

20. Following incubation at room temperature, briefly spin the tube and place on the magnetic rack for 5 minutes until the beads have collected to the wall and the solution is clear.

21. Carefully remove the supernatant with a pipette without disturbing the beads. The supernatant is enriched for microbial DNA and may be saved and purified by bead cleanup (Auxiliary protocol A). Otherwise, discard the supernatant.

22. Add 1 ml of 1 bind/wash buffer (kept at room temperature) to wash the beads.

	If processing in a microplate, decrease the volume of wash buffer to 100 µl.

23. Carefully remove and discard the wash buffer with a pipette without disturbing the beads.

24. *Optional*. Add 100 µl of 1x bind/wash buffer (kept at room temperature) to the beads. Pipette the mixture up and down a few times to mix.

	We have found that an additional wash with 100 µl of 1x bind/wash buffer followed by rotation (steps 24-27) substantially improved enrichment. To skip this wash, proceed to step 28.

25. Mix the beads by rotating the tube in a rotating mixer for 3 minutes at room temperature.

26. Briefly spin the tube and place on the magnetic rack for 2-5 minutes until the beads have collected to the wall of the tube and the solution is clear.

27. Carefully remove and discard the supernatant with a pipette without disturbing the beads.

## Eluting captured host DNA

The NEBNext Microbiome Enrichment Kit includes an elution protocol for captured DNA that includes digestion of DNA-bound MBD beads with proteinase K and elution with TE buffer. We have found that elution with 2 M NaCl is just as effective, is less time consuming, and conserves proteinase K. Most importantly, we have found that DNA samples eluted with 2 M NaCl and purified by bead cleanup can be further enriched in a repeat enrichment reaction. DNA samples eluted with proteinase K and TE buffer and purified by bead cleanup in contrast produced miniscule yields following a repeat enrichment reaction.

28. Add 100 µl of 2 M NaCl (prepared in step 5 and kept at room temperature) to the beads. Pipette the mixture up and down a few times to mix.

	If large numbers of samples are being processed, considering lowering the elution volume such that the combined volume of DNA and SPRI beads (see Auxiliary protocol A; step 1) does not exceed the capacity of microplate wells and thereby preclude the ability to parallelize bead cleanups.

29. Mix the beads by rotating the tube in a rotating mixer for 3 minutes at room temperature.

30. Briefly spin the tube and place on the magnetic rack for 2-5 minutes until the beads have collected to the wall of the tube and the solution is clear.

31. Carefully remove the supernatant to a fresh microcentrifuge tube and discard beads.

32. Proceed to bead cleanup to purify sample (Auxiliary protocol A). 

# Auxiliary protocols

## Auxiliary protocol A: Bead cleanup

Portions of this protocol are modified from Pacific Biosciences protocol # 001-252-177-03.

**Materials and reagents**

* Pre-washed magnetic SPRI beads, prepared following Rohland and Reich (2012)
* 70% ethanol, freshly prepared
* 1x TE buffer
* Magnetic stand
* Centrifuge

1. Add 1.5-1.8x volume of pre-washed magnetic beads to DNA in a 1.5 ml tube.

	If the combined volume of beads and DNA does not exceed the capacity of the tube or well, large numbers of bead cleanups can be conducted in parallel on a microplate.

2. Mix the bead/DNA solution thoroughly by pipetting up and down several times.

3. Vortex the beads for 5 minutes.

4. Briefly spin the tube and place on the magnetic rack for 5 minutes or until the solution is clear.

5. Carefully remove and discard the supernatant without disturbing the beads.

6. Wash beads with freshly prepared 70% ethanol. Wait 1 minute, then pipette and discard the ethanol.

	Use a sufficient volume of 70% ethanol to completely cover the bead pellet (e.g., 100 µl for microplates and 400 µl for 1.5 µl tubes). Slowly dispense the 70% ethanol against the side of the tube opposite the beads. Do not disturb the bead pellet.

7. Repeat step 6 above.

8. Remove residual 70% ethanol and air-dry the bead pellet for 1 minute.

	Spin at full speed for 2 minutes in order to collect residual 70% ethanol. Then place on the magnetic rack for 30 seconds before pipetting the residual 70% ethanol and air-drying for 1 minute.

9. Resuspend the beads in 30-40 µl of 1x TE buffer or another suitable DNA stabilization buffer.

10. Vortex for 1 minute, then incubate for 2 minutes. Spin the sample at full speed to pellet beads. Return to the magnet and collect the supernatant in a new 1.5 ml microcentrifuge tube.

11. Following bead cleanup, quantify with a fluorometer or spectrophotometer. Validate enrichment by qPCR (Auxiliary protocol B). Enriched DNA can be sequentially enriched by repeating the enrichment protocol adding 30 µl of the enriched product to step 17.

## Auxiliary protocol B: qPCR estimation of enrichment

**Materials and reagents**

* Extracted fDNA of known quantity
* 2x SYBR Green master mix (e.g., Qiagen catalog number 204143 or ThermoFisher Scientific catalog number A25780)
* Taxon-specific primers
* DNA standards

	For host quantification, standards can be created by performing a dilution series (i.e., 10ng/µl, 1ng/µl, 0.1ng/µl, 0.01ng/µl) of high-quality gDNA (such as blood or liver DNA) from a suitable taxon.

* qPCR instrument

1. Run samples and standards at least in duplicate. We also recommend running a positive and negative control with each set of quantifications.

2. Use primers specific to the analysis
	
	a. The proportion of host DNA can be quantified by comparing qPCR results using host-specific primers to the absolute quantification estimated by some independent means (e.g., fluorometer or spectrophotometer). For our baboon DNA quantifications, we use universal mammal primers for the *c-myc* gene (Morin <em>et al.</em> 2001):

	b. Enrichment of DNA captured with MBD beads can be quantified as above using host-specific primers with enriched methylated host DNA. Alternatively, enrichment can be estimated by observing the n-fold decrease in quantified levels from unenriched to enriched samples using the universal 16s rRNA primer (Corless <em>et al.</em> 2000). 1 µl of unenriched DNA can be diluted to the concentration of the enriched sample prior to qPCR to standardize concentrations. Because MBD enrichment can in principle be biased towards densely methylated areas of the host genome, we prefer the latter method for estimating enrichment success.

```
>cmycF
GCCAGAGGAGGAACGAGCT

>cmycR
GGGCCTTTTCATTGTTTTCCA

>16s_F
CCATGAAGTCGGAATCGCTAG

>16s_R
GCTTGACGGGCGGTGT
```

3. Set up qPCR reactions in a 20 µl total volume containing 1x of SYBR Green master mix, 0.5 mM of each primer, and 1 µl of DNA.

4. Run samples in the qPCR instrument at 95°C for 15 minutes, followed by 50 cycles of 94°C for 15 seconds, 59°C (for all primers specified above; adjust for other primers) for 25 seconds, and 72°C for 20 seconds.

# References

Corless, C. E., Guiver, M., Borrow, R., Edwards-Jones, V., Kaczmarski, E. B., & Fox, A. J. (2000). Contamination and sensitivity issues with a real-time universal 16S rRNA PCR. <em>J Clin Microbiol</em>, 38, 1747–1752.

Morin, P. A., Chambers, K. E., Boesch, C., & Vigilant, L. (2001). Quantitative polymerase chain reaction analysis of DNA from noninvasive samples for accurate microsatellite genotyping of wild chimpanzees (<em>Pan troglodytes verus</em>). <em>Mol Ecol</em>, 10, 1835–1844.

Rohland, N., & Reich, D. (2012). Cost-effective, high-throughput DNA sequencing libraries for multiplexed target capture. <em>Genome Res</em>, 22, 939–946.

