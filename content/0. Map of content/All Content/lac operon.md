---
title: lac Operon
---
A highly conserved DNA sequence that contains both coding and regulatory genes, all related to the metabolism of lactose.
___
## Cis-Regulatory Elements:
Nucleotide sequence elements that can only regulate DNA that is Upstream or downstream from it on the same nucleic acid chain.

- **Promoter Sequence**  
	- non-coding DNA sequence upstream from the operon...     
	- recognized by [[RNA polymerase]] which binds to the sequence in order to initiate expression of the operon downstream. <br>
</br>
- **$\large{lacO}$ Operator Sequence**  
	non-coding DNA sequence upstream from the operon, controls the operons inducible expression.<br>
	</br>
	- **$\large{[O^c]}$ Constitutive operator mutant**  
		Mutant operator sequence that looses affinity for the Repressor protein... Meaning that it can no longer be repressed... this results in the downstream Operon being expressed continually (constitutive expression), regardless of the presence of other Regulatory elements.
___
## Trans-Regulatory Elements:
Protein Regulatory elements that can act on any DNA in the cell.

- **$\Large{lacI}$ Repressor Protein Gene:**  
	- Protein coding gene, upstream from the operon...  
	- The resulting repressor protein will bind to the operator sequence and represses the expression of the operon...  
	- it loses affinity for the operator when lactose is present in the cells nucleus (lactose isoform allolactose binds to allosteric site on the protein)...  
	- Allowing for the operon to be inducible, only when its needed (to break down the lactose)...<br>
	</br>
	- **$\large{[I^-]}$ Gene Mutant**  
		- Protein shape is altered in a way that it can no longer bind to the operator...  
		- causes constitutive expression of the operon.	<br>
	</br>
	- **$\large{[I^s]}$ Superrepressor Gene Mutant**  
		- The allosteric site on the protein changes shape, in a way that it looses affinity for the inducer ([[allolactose]])...  
		- Because the inducer can no longer bind, the superrepressor can bind to the operator permanently...  
		- Causing expression of the operon to be silenced...  
		- Lactose is not able to be metabolized.
---
## Gene Coding Constituents:

- $\large lacZ$ Gene   
	Codes for [[beta-galactosidase|β-galactosidase]],  
	An enzyme that Hydrolyzes lactose into galactose and glucose.<br>
	</br>
- $\large lacY$ Gene  
	Codes for [[lac permease]],  
	A Membrane protein that pumps lactose into a cell.<br>
	</br>
- $\large lacA$ Gene  
	Codes for transacetylase,   
	An enzyme adds an [[acetyl group]] ($\ce{CH3CO}$) to lactose.
___

# Summary Table

|          Gene |     Allele     | Result                                | Effect                                                                                                      | Operon<br>Expression | Reg-<br>ulation |              Sequence               | Allele Type                       |
| ------------: | :------------: | ------------------------------------- | :---------------------------------------------------------------------------------------------------------- | :------------------: | :-------------: | :---------------------------------: | :-------------------------------- |
| $\large lacI$ |  $\large I^+$  | Repressor <br>Protein <br><br>        | Binds to operator in absence of lactose.<br><br>disassociates from operator region when lactose is present. |      inducible       |     Trans -     |     upstream of<br>$lac$ operon     | wild type <br>allele              |
|   $\llcorner$ |     $I^-$      | Repressor <br>Protein                 | Repressor is not produced or cannot bind to operator.<br><br>operon expression is continuous<br>            |     Constitutive     |     Trans -     |              $$\mid$$               | Mutant<br>`Deleterious`<br>allele |
|   $\llcorner$ | $I^{\large s}$ | Superrepressor <br>Protein<br><br>    | $lac$ operon expression <br>silenced, lactose is not <br>able to be metabolized.                            |   Always repressed   |     Trans -     |          <br><br>$$\perp$$          | Mutant<br>`transformative` allele |
| $\large lacO$ |  $\large O^+$  | Operator <br>sequence                 | normal function                                                                                             |      inducible       |      cis -      | operator gene, <br>in $lac$ operon  | wild type <br>allele              |
|   $\llcorner$ |  $\large O^c$  | Operator <br>sequence                 | operator cannot be repressed.<br>                                                                           |     Constitutive     |      cis -      |              $$\perp$$              | Mutant<br>`transformative` allele |
| $\large lacZ$ |  $\large Z^+$  | β-galactosidase                       | Functional Enzyme<br>(Hydrolyzes lactose into <br>galactose and glucose)                                    |        $$-$$         |      $$-$$      | 1st coding gene <br>in $lac$ operon | wild type <br>allele              |
|   $\llcorner$ |  $\large Z^-$  | No <br>β-galactosidase                | Non-Functional                                                                                              |        $$-$$         |      $$-$$      |              $$\perp$$              | Mutant<br>`Deleterious`<br>allele |
| $\large lacY$ |  $\large Y^+$  | Lac permease<br>(Membrane<br>protein) | Functional Enzyme<br>(Transports lactose from <br>extracellular environment,<br>into cell)                  |        $$-$$         |      $$-$$      | 2nd coding gene <br>in $lac$ operon | wild type <br>allele              |
|   $\llcorner$ |  $\large Y^-$  | No <br>Lac permease                   | Non-Functional Enzyme                                                                                       |        $$-$$         |      $$-$$      |              $$\perp$$              | Mutant<br>`Deleterious`<br>allele |
| $\large lacA$ |   $\large A$   | transacetylase <br>enzyme             | adds an acetyl group <br>($\ce{CH3CO}$) to lactose.                                                         |        $$-$$         |      $$-$$      | 3rd coding gene<br>in $lac$ operon  | wild type <br>allele              |
___
## Other Info  

**Differentiation between no expression and basal expression:**
	No expression 
		only when $Z^-, Y^-$. 
		With mutant structural genes 
	Low or Basal expression
		if $O^-, I^S$ 
		With mutant regulatory genes

**Operon Transcription**
- The operon is always transcribed as a single [[polycistronic]] mRNA, with the coding genes in the following order...  
	$5'-lacZ-lacY-lacA-3'$  

**HTH motif**
- specific sequences in the $\large \alpha$ Helical structure of a DNA binding protein complex that recognize nucleotide sequences. 
- the helical shape surrounding the motif helps to create weak polar bonds with nucleotide bases through the major groove of the DNA Double helix, binding the two together. 

**Glucose Regulation** (Catabolite Repression)
- the lac operon is also regulated by Glucose (the preferred sugar). if both are present in the cell, only glucose is utilized until it runs out, and then lactose is used. 
- Glucose levels control cAMP levels indirectly by decreasing [[adenyl cyclase]], an enzyme that converts [[ATP]] into [[cAMP]]. 
- High glucose levels = Low cAMP levels 
- low/no glucose = high cAMP levels.

**cAMP** (cyclic adenosine monophosphate)
- high cAMP levels = low sugars = ramp up lac operon production to utilize stores, and generate glucose.

**CRP** (cAMP Receptor Protein)
- cAMP will bind to the allosteric site of CRP, forming the CRP-cAMP Complex.

**CRP-cAMP Complex**
- formation of the complex alters the shape of CRP, in a way that gives it affinity for binding to a section of the lac operons promoter region.
- the complex binds to a rotationally symmetric section of the lac promoter region as a dimer.
- A positive regulator for the lac operon (catabolite regulation) 
- its binding recruits RNA polymerase, enhancing transcription initiation frequency... 

**IPTG** 
- a synthetic lactose stand-in that can not be broken down. in order to include recombinant DNA sequences controlled by lac operon 

**Rotational Symmetry**
- seen in nucleotide sequences that transcriptional factors bind to. reflecting that TFs are often assembled from identical subunits. the operator region has rotational symmetry that allows for tetramer repressor proteins to bind and form a loop in the DNA.
- binding of all 4 subunits of a tetramer produces the highest level of repression.

**lac operon applications in synthetic biology**
- Overproduction of target gene
	synthetic plasmid vectors synthesized with the lac operon control region, and recombinant coding genes allows for the high expression of target proteins or enzymes. (ex. [[growth hormone|hGH]] or, insulin overproduction in bacterial cells for )
- $lacZ$ as reporter gene
	coding region of lacZ can be fused to cis-acting regulatory regions from other genes... (       )