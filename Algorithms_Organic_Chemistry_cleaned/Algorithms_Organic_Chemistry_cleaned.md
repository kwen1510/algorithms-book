# Algorithms (Organic Chemistry)

## Chemical Bonding II (hybridisation)

### Determining hybridisation of atom

- Look at the number of electron density regions (sum of bond pairs and lone pairs)
    - 2 regions – sp
    - 3 regions – sp2
    - 4 regions – sp3
- Note: There could be cases where the question states that the molecule is planar/equal bond length etc. This suggests that there is resonance. In that case, even if an atom has 4 electron density regions, it can be sp2 hybridised.



![](<images/Algorithms_Organic_Chemistry_cleaned_-7c7b7029fc862a51.png>)

### Pyrrole (aromatic)

- For allocation of electrons, see **Appendix C**



## Intro to organic Chemistry

### Drawing all isomers

- Draw all isomers with given formula
    - Loop through the following process
      - Chain isomers
        - Positional isomers
          - Stereoisomerism (check the entire molecule for chiral carbons and not where you add the new group)



![](<images/Algorithms_Organic_Chemistry_cleaned_-6bc202c35ba97830.png>)

_(The carbon in which the Cl is added to is not chiral, but adding the Cl made another carbon atom chiral)_

- Draw all isomers formed from a reaction (e.g. FRS of alkanes)
    - Template stays the same
    - This is a question about positional isomers and possibly Enantiomerism
- Note: The follow molecule has meso compounds. You need to know how to rotate about the single bond



![](<images/Algorithms_Organic_Chemistry_cleaned_2869b8e0a9cb672e.png>)

## Alkanes

### Counting number of types of hydrogens

- See **Appendix A**
- Alternative methods include replacing H’s and see which structures give unique products (ignoring stereochemistry)
- Another alternative method is to look for symmetry in the bonds
- Note: If need be, you can rotate a single bond



### Drawing the free radical substitution mechanism

- Step 1: Initiation
- Step 2: Propagation
- Step 3: Termination
    - Mix and match the radicals and connect them together (like joining dots)
    - There should be no radicals left after this step
    - Typical mistake



![](<images/Algorithms_Organic_Chemistry_cleaned_1e5dfad329547c05.png>)

### Determining proportion of different products

- If the question does not ask for it, we assume that all the hydrogens are of similar reactivities



![](<images/Algorithms_Organic_Chemistry_cleaned_757f9bbaaec95b63.png>) **A : B = 2:6 = 1:3**

- If the question provides us with data (rate of formation of carbon radical: 3o > 2o > 1o, we will consider that in our answer (e.g. rate of 2o : rate of 1o = 5 : 2)



![](<images/Algorithms_Organic_Chemistry_cleaned_9ab575eb43e3ac1.png>) **A : B = 2 x 5 : 6 x 2 = 10 : 12**

### Drawing stereoisomers of cycloalkanes

- To draw the enantiomer, draw the molecules and draw its reflection in a mirror plane



![](<images/Algorithms_Organic_Chemistry_cleaned_60ccf84639b31a1f.png>)

- Shortcut: Simply flip the “up” bonds into “down” bonds



![](<images/Algorithms_Organic_Chemistry_cleaned_673a5beca06b2304.png>)

## Alkenes

### Calculating degree of unsaturation (DoU)

- Use the number of carbons to calculate the total H if it were an alkane (CnH2n+2)
- Find the number of H atoms that are “missing”
- For every 2 “missing” H, 1 pi bond/ring is formed
    - E.g. benzene has DoU = 4 (3 x C=C, 1 ring)
    - C6H6 🡪 8 H’s missing



### Drawing the electrophilic addition mechanism (See **Appendix B** )

- Take note of the reagents (Br2 in CCl4 and Br2 is H2O is very different)
- Pi bond of alkene (nucleophile) attacks the d+ carbon of the electrophile
- Look at the carbocation (‘+’ charge should be on the carbon with the most electron donating R groups)
- Look at the list of nucleophiles and decide on which attacks the carbocation (electrophile)
    - If the solvent is reactive (i.e. H2O), it will form the major product because it is in large excess
    - Remember to remove H+ from the water molecule



![](<images/Algorithms_Organic_Chemistry_cleaned_-15130a23414ef1ac.png>)

(A common mistake is to skip the first step and use OH- to attack the carbocation – this is incorrect as OH- is in low concentrations)

### Oxidative cleavage questions

- Breaking
    - Cut all C=C double bonds
    - For every C-H bond, add an O atom inbetween them
    - Should end up with ketones, carboxylic acids or CO2 \+ H­2O
    - Points to note: 
      - In the alkaline condition, CO32- is formed instead of CO2 \+ H2O



![](<images/Algorithms_Organic_Chemistry_cleaned_420e96c44425edb2.png>)

### Structure of CO32-

      - If ethanedioic acid is formed, further oxidation will give you CO2 and H2O. It will depend on the question. In some cases where you see C2H2O4 (ethanedioic acid) as the product, you can just assume the oxidation process is not completed.
      - If 1 reactant 🡪 1 product (with the same number of carbons, this means that the molecule is a ring (oxidative cleavage opened up the ring). This also applies to odd cases (you expect 3 fragments, but you get 2).



![](<images/Algorithms_Organic_Chemistry_cleaned_-29c5ad97b66532f0.png>)

### Ethanedioic acid

- Piecing back
    - CO2 are from terminal C=C or for ethanedioic acid (you might consider this in more challenging questions)
    - Reverse ketones into ![](<images/Algorithms_Organic_Chemistry_cleaned_6a660e0c4f0fac6e.png>)
    - Reverse RCOOH into ![](<images/Algorithms_Organic_Chemistry_cleaned_235035424e98c145.png>)
    - Face the groups together and join them together (the one with one connecting group should be at the ends. The fragment with two or more connecting groups should be in the middle.



![](<images/Algorithms_Organic_Chemistry_cleaned_-48840f19abf25f5d.png>)

- **Variations:** Double bonds in rings (with ethanedioic acid as product)



![](<images/Algorithms_Organic_Chemistry_cleaned_-6f13d41b99c0b2df.png>)

## Arenes

### Drawing the electrophilic substitution mechanism

- Using directing effects to see where the new group is added to
- Generate the electrophile with the correct equation
- Draw the standard mechanism
    - Benzene ring attacks the electrophile (generated in the previous step) [slow step]
    - H+ is removed and the electrons are returned into the benzene ring [fast step]
    - Generate the catalyst (if applicable)



Note: For phenols and phenylamines, you do not need to generate the electrophile. For the first step of the mechanism, you can simply follow that in electrophilic addition.

## Halogen Derivatives

### Drawing the nucleophilic substitution mechanism

- Determining ­SN1 or SN2 ­reactions
    - Degree of substitution (primary = SN2, tertiary = S­N1)
      - Note: some primary RX can undergo S­N1 due to resonance with the benzene ring/double bond. It depends on the question.
      - ![](<images/Algorithms_Organic_Chemistry_cleaned_-5d36b28e2108a0a1.png>)
    - Optical activity (Racemic mixture - S­N1, able to rotate plane polarised light - S­N2)
    - Kinetics data (look at the rate equation. If it does not contain the nucleophile - S­N1, vice versa)



### Drawing nucleophilic substitution mechanism

- Take note of neutral vs negatively charged nucleophiles
- SN1
    - Break the C-X bond (heterolytic) [slow]
    - Use the nucleophile to attack the carbocation from **top** and **bottom** [fast]
    - If applicable, remove the last H+ and return its electrons (especially for synthesis of amines – From neutral nucleophiles)



![](<images/Algorithms_Organic_Chemistry_cleaned_-6742709ba17f8bca.png>)

- SN2
    - Nucleophile attacks the molecule from the back



![](<images/Algorithms_Organic_Chemistry_cleaned_-1020cfb41c0aac6c.png>)

    - Show inversion of symmetry
    - If applicable, remove the last H+ and return its electrons



## Hydroxy Compounds

### Answering acidity questions

- Draw out the conjugate bases
- Use electronic effects (electron donating/withdrawing through inductive/resonance) to explain if the negative charges are **intensified** or **dispersed**.
- The more dispersed the negative charge, the more stable the conjugate base, the more acidic the compound.
- Note: Inductive effect is distance dependent



### Additional tips:

- Be specific in the way you describe hydroxy compounds (e.g. 1o alcohol, 2o alcohol, 3o alcohol, phenol). Their oxidation products are different/some do not undergo oxidation reactions
- Use K2Cr2O7 instead of KMnO4 for normal oxidation. It allows for better control (you can form aldehydes) and it does not have many other side reactions (KMnO4 can also do side chain oxidation of alkylbenzenes and oxidative cleavage of alkenes)



## Carbonyl Compounds

### Reactivity of carbonyl electrophile

- Steric effect: 2 R groups/benzene ring > 1 R group
- Electronic effect: 2 electron donating groups/delocalisation of electrons in a resonance structure makes the carbonyl carbon less electron deficient (look at d+)



### Drawing nucleophilic addition mechanism

- Generate the CN- nucleophile with NaOH or NaCN
- Use the CN- (nucleophile) to attack the electron deficient carbonyl carbon. Push the electrons upwards to form O-
- Use the lone pair of electrons from O- to abstract a H+ from HCN, regenerating the CN- catalyst



## Carboxylic Acid and Derivatives

- Tip: Be open to the idea of intramolecular condensation reactions



![](<images/Algorithms_Organic_Chemistry_cleaned_-7bf514101695cd0e.png>)

- Hydrolysis of esters/amides
    - Watch out for the reaction medium (acidic/alkaline). It will affect the products formed.
      - Esters:
        - Acidic – RCOOH and ROH; RCOOH and PhOH
        - Alkaline – RCOO-Na+ and ROH; RCOO-Na+ and PhO-Na+
      - Amides:
        - Acidic – RCOOH and RNH3+
        - Alkaline – RCOO-Na+ and RNH2



## Nitrogen Compounds

### Determining basicity

- Discuss about the availability of the lone pair of electrons
- The explanation is similar to that when we determine acidity. Instead of dispersing charges (since there are no charges here), we use the availability of the lone pair of electrons
- Note: Nucleophilicity follows the same explanation, but for bigger nucleophiles, they rather act as bases because it is easier to remove peripheral H atoms than attack the central carbon



![](<images/Algorithms_Organic_Chemistry_cleaned_-24d373289120edb0.png>)

The bottom reaction is less likely because the amine (exaggerated) is too large

### Titration curves of proteins

- Assume the molecule is in a very acidic solution and protonate all protonatable groups (RNH3+ and RCOOH)
- Once each pKa value is crossed, remove the more acidic H+ (assign the acidity based on our earlier discussions)
    - RCOOH more acidic than RNH3+
    - More stable RCOO- is more acidic
    - Less available lone pair in RNH2 is more acidic (weaker base = stronger acid)
- Variation
    - Drawing a zwitterion
      - Do the above “titration curve” to determine net zero charge
      - Shortcut – transfer the most acidic H+ to the most basic N atom
    - Extension into pKa question with buffer calculations
      - See chapter on _acid-base equilibria_



### Reassembling partial hydrolysis fragments

- Arrange the fragments vertically
- Overlap portions that are similar
- Combine into one sequence
- Note: 
    - Some questions will tell you the total number of units in a sequence. Look out for that.
    - **DO NOT** flip the fragments around. They are connected correctly from the N to C terminus



## Synthesis questions

### General tips

- Identify changes in functional groups
- Look at typical functional groups with common mechanisms
    - RX – Nucleophilic substitution/elimination
    - ROH – Substitution (to form RX)/elimination
    - Alkenes – Electrophilic substitution
    - Arenes – Electrophilic substitution
- Calculate DoU to obtain number of pi bonds or rings
- Look at the formula of the reactant and products and deduce possible reactions
    - Loss of a small molecule without increase in DoU – condensation
    - Loss of a small molecule + increase in DoU – elimination reaction (might be cylic condensation also)
    - Step-up reactions
      - Formation of C-C bonds: CN, Friedal Kraft’s alkylation or acylation
      - Condensation reactions
    - Step-down reactions 
      - Oxidation reactions
        - Oxidative cleavage
        - Side-chain oxidation
        - Iodoform test
      - Hydrolysis



### Arenes

- Take note of directing groups (takes precedence)
- Consider electron donating/withdrawing effects



### Alkenes

- Alkenes are useful intermediates
    - 1 🡪 2 functional groups



![](<images/Algorithms_Organic_Chemistry_cleaned_654c8a6df3dd0685.png>)

    - 1 🡪 2 different functional groups



![](<images/Algorithms_Organic_Chemistry_cleaned_5099e6f97ec6c541.png>)

    - Moving of X positions



![](<images/Algorithms_Organic_Chemistry_cleaned_-5844781efbc45b61.png>)

    - Oxidative cleavage (to remove C)



### RX

- Useful to extend C with NaCN
- Useful for elimination
- Useful for Nu Sub to form alcohols



### ROH

- Useful for oxidation
- Useful for elimination
- Useful for substitution to form RX



### Carbonyls

- Useful for extending C chain with HCN (and NaCN/NaOH)



### Carboxylic acid and derivatives

- Acyl chlorides are good for forming esters and amides
- Carboxylic acids do not undergo condensation reactions with phenols (see example below)



![](<images/Algorithms_Organic_Chemistry_cleaned_-6250362c7c3b468a.png>)

- Amines do not react with carboxylic acids to form amides (not in the H2 syllabus). Instead, an acid-base reaction will occur.



## Distinguishing test questions

- Identify differences in functional groups
    - Look for specific reactions for the individual functional groups
    - If the compounds are gases, you will have to bubble them through a solution to test it
- If the forms are different (i.e. isomers, less C etc)
    - Esters/amides
      - Hydrolyse first



![](<images/Algorithms_Organic_Chemistry_cleaned_31db8577893998d4.png>)

After hydrolysis, the one on the left produces an alcohol that can be oxidised

    - Iodoform test



![](<images/Algorithms_Organic_Chemistry_cleaned_-7702d9a0f15187ce.png>)

The molecule on the right gives a positive iodoform test (after hydrolysis – NaOH warm does the hydrolysis first)

    - Dienes



![](<images/Algorithms_Organic_Chemistry_cleaned_1d28e20314235790.png>)

The molecule on the left gives CO2 and H2O after oxidative cleavage (ethanedioic intermediate is formed)

    - Side-chain oxidation



![](<images/Algorithms_Organic_Chemistry_cleaned_744a82ea999836ee.png>)

When both reacts with hot acidified KMnO4, the latter gives CO2 on top of decolourisation of KMnO4

- Experiments must give observable changes
    - Gas evolved, colour change, formation of precipitate, state changes (e.g. miscibility)
    - Cases
      - 1 has observation, the other does not
      - Both have observations, but one has more



![](<images/Algorithms_Organic_Chemistry_cleaned_6a3ec4dd19214bc5.png>)

When both reacts with hot acidified KMnO4, the latter gives CO2 on top of decolourisation of KMnO4

- Note: 
    - The experiments should be doable in the lab and it does not take too long (i.e. you cannot use reactions with high pressure (e.g. 160 atm), or use heat with reflux (since it takes too long)



## Structural elucidation questions

- Calculate DoU to obtain number of pi bonds or rings
- Look at the formula of the reactant and products and deduce possible reactions
    - Loss of a small molecule without increase in DoU – condensation
    - Loss of a small molecule + increase in DoU – elimination reaction (might be cylic condensation also)
    - Step-up reactions
      - Formation of C-C bonds: CN, Friedal Kraft’s alkylation or acylation
      - Condensation reactions
    - Step-down reactions 
      - Oxidation reactions
        - Oxidative cleavage
        - Side-chain oxidation
        - Iodoform test
      - Hydrolysis
- Watch out for the reagents used and how they affect the formula
    - Br2(aq) can do tri-substitution of Br on phenol/phenylamine
    - Note: each Br2 molecule can add up to 2 Br atoms to an alkene but only substitute 1H on a benzene ring
    - Each mole of -OH groups react with 1 mole of Na to form 0.5 mol of H2 (can try balancing for the other cases – e.g. reaction with NaOH, NaHCO3, Na2CO3)
- Classic cases
    - Oxidative cleavage/oxidation
      - Oxidative cleavage can only give you ketones, carboxylic acids and CO2
      - If the number of O does not change (but number of H changes), the previous -OH group is a secondary alcohol (forms a ketone)
    - Reassembling of fragments after oxidative cleavage
      - CO2 and H­2O
        - From terminal
        - From ethanedioic acid (![](<images/Algorithms_Organic_Chemistry_cleaned_-1957f7ee169d4dd.png>))
    - Multi-substitution unto phenol/phenylamine with Br2(aq)
      - 3 sub – 2,4,6 sub
      - < 3 sub – 2,4,6 positions (relative to -NH2 and -OH) blocked
      - Note: Br can also be added to other pre-existing alkenes around
    - Molecule is neutral
      - No Ph-OH, no RCOOH
      - No Ph-NH2, no amines
      - Can be alcohols, carbonyls, RCN, amides
- Take note of multiple reactions/side reactions
    - KMnO4 \+ H2SO4 \+ heat can do acidic hydrolysis and strong oxidation
    - NaOH + heat can do nucleophilic substitution of R-X and hydrolysis at the same time
- Starting points
    - Rarely do you start piecing from the top, but there are cases where you can try a random starting molecule
    - If the question has an oxidative cleavage reaction and it breaks into the fragments, you can start off with some of the fragments
      - Some fragments may be small enough to guess (e.g. there is only one way to draw 3 carbons. 4 can be linear or branched)
      - Take note that oxidative cleavage can only give you ketones, carboxylic acids and CO2



### C2H2O4

![](<images/Algorithms_Organic_Chemistry_cleaned_36cdbfe6ae7dde14.png>)

### C2H4­O2

![](<images/Algorithms_Organic_Chemistry_cleaned_-350684754c0d428e.png>)

### C3H4O3

![](<images/Algorithms_Organic_Chemistry_cleaned_221b1c7239679cd0.png>)
  
- Once you have drawn the structure, put the structure back into the question and check if it ticks all the boxes



## Appendix A – Determining the types of H atoms

### Consider the following molecule (2-methylbutane):

![](<images/Algorithms_Organic_Chemistry_cleaned_558c2168a40b0a81.png>)

Let us look at the groups that each of the carbons are connected to.

| Carbon label | Groups Connected |
| --- | --- |
| (a) | 3 H atoms, ![](<images/Algorithms_Organic_Chemistry_cleaned_6f30ff4c3e659105.png>) |
| (b) | 2 H atoms, 1 –CH­3 group, ![](<images/Algorithms_Organic_Chemistry_cleaned_35cbaf043da7063.png>) |
| (c) | 1 H atom, 2 –CH­3 groups, ![](<images/Algorithms_Organic_Chemistry_cleaned_-6877896bb6b0b03f.png>) |
| (d) | 3 H atoms, ![](<images/Algorithms_Organic_Chemistry_cleaned_-1155e884313bd0e1.png>) |
| (e) | 3 H atoms, ![](<images/Algorithms_Organic_Chemistry_cleaned_-1b61a691b1b2bc0a.png>) |
  
- The wriggly lines denote the location where the bond fragment starts.

From the table, we can observe that carbons (d) and (e) are similar. Hence, their H atoms are equivalent (in similar environments). 

Even though carbon (a) is also a primary carbon, it is not the same as carbons (d) and (e).

## Appendix B – Detailed explanation for the electrophilic addition reaction

![](<images/Algorithms_Organic_Chemistry_cleaned_-164822f356801621.png>)

HBr is already polar, hence you can assign a δ⁺ and δ⁻ to the H and Br atoms respectively.

If the reagent is replaced with Br₂, the electron-rich alkene will polarise the electron cloud to induce a δ⁺ and δ⁻ on the Br atoms.

![](<images/Algorithms_Organic_Chemistry_cleaned_-5d5dfbbd56f7014a.png>)

Electrons flow from the source (π electrons on C=C) to the sink (H atom), breaking H–Br bond. (i.e. Nucleophile to electrophile)

Two intermediate carbocations can be formed. The carbocation on the left is more stable as it has more electron-donating alkyl groups connected to it. It will help to disperse the positive charge on the carbocation. Hence, it will be formed faster.

- **Note:** Identify if the intermediate (carbon) is electron-rich or poor.
In this case, it is **electron-poor** (it has 6 valence electrons, which means it needs 2 more electrons — hence it is electron-poor).

![](<images/Algorithms_Organic_Chemistry_cleaned_-49b927e9c12383d2.png>)

Notice the alkene has converted from a nucleophile to an electrophile (intermediate).

Hence, the second step is an attack on the carbocation by a nucleophile.  
In our case, only Br⁻ can act as a nucleophile (CCl₄ is inert).  
Hence, only Br⁻ can attack the carbocation, which will give us the product.

The **major product** will agree with **Markovnikov’s rule**.

- **If you are unable to see the intermediate from the skeletal structure, redraw the skeletal structure with the relevant C and H for clarity.**

### Extension questions

1. Since Br2 is non-polar, how does it obtain the 𝛿+ and 𝛿- charge?



When Br2 comes into close proximity to the electron rich C=C, the C=C will polarise the Br2 molecules electron cloud to induce a dipole (recall instantaneous dipole – **induced** dipole interaction). This gives the 𝛿+ on the Br atom on the near-side and 𝛿- on the Br atom on the far-side. 

2. Why does Br2(aq) give me the –Br and –OH instead?



In the second step of the mechanism, while choosing the nucleophile, H2O can also act as a nucleophile (on the other hand, CCl4 is inert). Since H2O is in **huge excess** (since it is the solvent), it is more like to act as a nucleophile and attack the carbocation than Br-. 

3. Where does the –OH in question 2 get connected to?



Notice that the –OH only gets added unto the molecule after it attacks the carbocation. Hence, it will only be added to the “positive” carbon in the carbocation (This is a variant of the Markonikov’s rule).

4. Why can HBr act as a nucleophile in the nucleophilic substitution mechanism of alcohols and an electrophile in the electrophilic addition mechanism of an alkene?



If you take a look at the current mechanism, Br- acts as a nucleophile in the second step (it attacks the carbocation). Therefore, the Br atom in HBr acts as a nucleophile (not an electrophile – the H atom is added first). Therefore, Br- is able to act as a nucleophile in both the nucleophilic substitution mechanism and in the second step of the electrophilic addition mechanism.

5. Why must HBr be dry? (Extension of hydroxyl compounds practice question 2(e))



If HBr is used in an aqueous solvent, H2O can also act as a nucleophile to attack the carbocation. Hence, the Br- will not get a chance to attack the carbocation (since H2O is in huge excess).

Also, for hydroxy compounds practice question 2(e), dry HBr is required for the nucleophilic substitution of alcohols because the –OH group of the alcohol needs to be protonated (to form –OH2+) by the H atom from HBr. H3O+ is not acidic enough to protonate the alcohol (See next page).

![](<images/Algorithms_Organic_Chemistry_cleaned_3bbffa55d3c22354.png>)

This is a good leaving group.

H₂O is a better leaving group than OH⁻. This is because OH⁻ is a better nucleophile than H₂O, which can reverse the reaction to reform the alcohol (nucleophilic substitution of RX to form ROH).

HBr has to be in an inert solvent or it will dissociate and form Br⁻ and H₃O⁺. H₃O⁺ is not able to protonate the hydroxyl group on the alcohol.

_Take note of the charge transfers and the balancing of charges._

6. Why does HBr not participate in the electrophilic substitution of arenes? (Extension of hydroxyl compounds practice question 2(e))



In the electrophilic substitution reaction of arenes, the first step of the reaction requires the generation of an electrophile.

### Step 1: Generation of electrophile

In a typical reaction of benzene with Br2, we will need a catalyst like FeBr3 to generate the Br+ electrophile (and [FeBr4]-).

For the reaction with phenols, there is no need for us to generate the electrophile as the benzene ring is activated (the hydroxyl group is strongly activating).

![](<images/Algorithms_Organic_Chemistry_cleaned_-460d1f7e77bbe4c.png>)

The presence of the hydroxyl group (strongly activating) activates the ring such that it is able to attack the Br₂ molecule straightaway (without a Lewis acid catalyst like FeBr₃). This follows the first polarisation step of the electrophilic addition mechanism.

In the second step, Br⁻ acts as a base and extracts the H atom to form HBr (white fumes). Take note that once again the electron flows from the source to the sink (bond lone pair to an atom).

The white fumes can only be seen in a non-aqueous/inorganic solvent where HBr is unable to dissolve and dissociate (e.g., in an aprotic medium).

Although Br⁻ can act as a nucleophile, if it attacks the ring (addition), it will destroy the aromaticity of the ring. Therefore, it acts as a base instead of a nucleophile.

## Appendix C – Assigning electrons in NO₂ orbitals

![](<images/Algorithms_Organic_Chemistry_cleaned_-54b787498449204c.png>)

1. Since there is resonance, all 3 atoms must have a p-orbital (hence sp² hybridised).

![](<images/Algorithms_Organic_Chemistry_cleaned_-2caa77660dac656a.png>)

2. Next, I fill in all the electrons in the molecule, including the lone pairs.

![](<images/Algorithms_Organic_Chemistry_cleaned_-5b28915a7274a19e.png>)

3. Let's focus on the first oxygen atom.
   - It has 3 sp² orbitals and 1 p-orbital.
   - It has a sigma bond, a pi bond and 2 lone pairs.

4. We know that a pi bond is formed by side-on overlap of p-orbitals, hence, the p-orbital is occupied by the pi electron.

![](<images/Algorithms_Organic_Chemistry_cleaned_-692b3ce17801acef.png>)

5. The last two lone pairs can then be placed in the remaining sp² orbitals.

![](<images/Algorithms_Organic_Chemistry_cleaned_-7336faeef8789818.png>)

6. Let’s now take a look at the N in the centre. Just like the O atom on the left, the pi electron lies in the p-orbital.

![](<images/Algorithms_Organic_Chemistry_cleaned_26af2c2cd4deed71.png>)

7. The remaining sigma bond, lone pair and dative bond can only be placed in the remaining 3 sp² orbitals.

![](<images/Algorithms_Organic_Chemistry_cleaned_-4525182f25ac3331.png>)

8. Let's now take a look at the last O atom. We know that the sigma bond has to be in the hybridised orbital.

![](<images/Algorithms_Organic_Chemistry_cleaned_-732285a498d3197d.png>)

9. Therefore, the 3 remaining lone pairs can only go to the remaining sp² orbitals.

![](<images/Algorithms_Organic_Chemistry_cleaned_210935ff6ca1c5e1.png>)
