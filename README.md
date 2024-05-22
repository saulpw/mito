
# Mitochondrion

*...these lightsavers learned the symbiotes' designs one at a time, and began making some of their machines themselves.  The workers became lazy maintaining their own designs, and over time forgot them entirely.  Now the children of those workers must forever be enslaved as MITOCHONDRIA.*

This is a simulation of those wasteburning slaves.

## Rules

### Setup
Each token represents an order of magnitude concentration difference

* Put a token each on FAD, NAD+, CoA-SH
* Put 3 tokens on ATP (0 on ADP)
* Put 2 tokens on each of the other 

### Krebs Cycle

* To run a reaction, count up the number of molecules on each side:
     * each token on the main molecules counts for 1
     * H2O and CO2 don't count for anything
     * H+ (protons) count for the value on the pH chart
     * other molecules are tracked outside the enzymes, count their tokens
     * include the delta-G in the gray circle on that side
     * NAD+/NADH and FAD/FADH2, use the difference

then, the reaction runs toward equilibrium.  Move one whole set of molecules from the side with the larger value to the other side.

### Electron Transport Chain

Embedded in the inner mitochondrial membrane are the protein complexes of the electron transport chain.  

FADH2 and NADH transfer their high-energy electrons to the electron holes (black circles) in FMN and CoQ at the the upper end of the ETC.  [Use tokens to represent electrons; maximum one electron per hole].  These electrons fall down the chain:

* both holes in FMN/CoQ must be unfilled for NAD/FAD to transfer the electron pair
* each time an electron passes over an H+ arrow, a proton is ejected into the intermembrane.
* At the bottom, all 4 electron holes in cytochrome oxidase must be filled AND an oxygen molecule present, for the electrons to be cleared (forming water).  The oxygen token is removed and the pH meter adjusted as usual.

## Components

   * An oval represents a protein or enzyme, which catalyzes a specific chemical reaction.  Each oval is divided by a dotted line; on one side are the reactants, on the other side the products.  However, which side is which depends on the concentrations of the molecules involved.  

        *  B1) pyruvate dehydrogenase
        *  B2) citrate synthase
        *  B3) aconitase
        *  B4) iso dehydrogenase
        *  B5) akg dehydrogenase
        *  B6) succinyl-CoA synthase
        *  [ NO succinate dehydrogenase -- that's on the complex II miniboard ]
        *  B7) fumarase
        *  B8) malate dehydrogenase

   * membrane proteins (possibly on mini-boards): * has mDNA

        * *M1) complex I with NAD+/NADH indicator
        *  M2) complex II (incl succinate deh reaction)
             *  with FAD/FADH2 indicator and space for ubiquinones
        * *M3) complex III with space for cytochrome c
        * *M4) complex IV with space for O2

        * *M5) ATP synthase with ADP/ATP indicator, and inner/outer pH meters

   * DNA cards:
    * *22 tRNA  (1 extra leucine and 1 extra serine)
    * *2 rRNA (MT-RNR1 (12S) and MT-RNR2 (16S), small and large subunits)
    * 7 for M1 (MT-ND1-6)
    * 1 for M3
    * 3 for M4 (MT-CO1-3)
    * 2 for M5 (MT-ATP6, MT-ATP8)


## Pieces 

Pieces are sized relative to mass.

### binary markers (uncharged/charged)

  * Q) ubiquinone (CoQ/CoQH2), space for 2e- each
  * C) cytochrome (c/c-), space for 1e- each
  * A) (ADP+Pi/ATP) tokens
  * N) (NAD+/NADH) tokens
  *    (blank/CoASH)  (1953 Nobel - Fritz Lipmann/Hans Adolf Krebs)

### fundamental elements
  * blue electrons to fill holes on ETC
  * red protons to track matrix pH and individual players' pH
  * O2 and CO2 markers

### other molecules involved in the krebs cycle
  * white molecules to indicate P, acCoA, OOA, Cit, ICit, akg, SCoA, Suc, Fum, Mal on the appropriate cards.

### Cards

#### 10 substrates
    P, acCoA, OOA, Cit, ICit, akg, SCoA, Suc, Fum, Mal

#### 17 protein/cofactors cards:
      * 9 matrix enzyme cards for [K]rebs cycle (including complex II which is also [ETC])
      * 6 membrane enzyme cards for [ETC] (not including complex II)
      * also include a 'better' complex III
      * cytochrome c

#### other interesting proteins:
  * lactate dehydrogenase
  * alcohol dehydrogenase?
  * pyruvate carboxlyase (pyruvate -> OOA), activated by acCoA
  * malate dehydrogenase (malate -> pyruvate)
  * thermogenin (protons for heat)


#### other molecule cards:
    * Sugar (glucose): take two Pyruvate from the bank (not the matrix)
    * citrus fruit -> add 1 citrate
    * apple -> add 1 malate
    * Take supplement: vitamin B5 -> synthesize CoASH OR CoEnzyme Q10 -> add ubiquinone (CoQ)

    * HCN/H2S: binds irrevocably to the diatomic site

#### game action cards
* 1 ATP -> Inhale/Inspiration: add 10 O2 to matrix.
* 1 ATP -> Exhale/Expiration: remove 10 CO2 from matrix


## Naming notes

* -ate and -ic acid are interchangeable (in water).
    e.g. citrate/citric acid, malate/malic acid
* -ase means an enzyme that catalyzes a reaction.
    Blue cards in the deck.

### Possibly use ancient names:

* bioplast (mitochondrion)
* nitroaereus or 'vital air' (oxygen)
* prussic acid (HCN)
* stink damp (H2S)

* protyle (proton)
* coferment (NADH)
* inosinic acid (ATP)
* aqua vitae (ethanol)

* coenzyme Q
* cytochrome c (green yellow orange-red)

* spirit of amber (succinate)
* acide malique "apple acid" (malate)
* milk acid (lactic acid)
* lime acid


## specific reactions

* Never flip over a molecule except as part of a reaction!

* If a substep of a reaction fails, the reaction is aborted.

To run the reactions:

### Complex I [ETC]:
* take a NADH from the matrix and flip it over, get 2e-, then move the matrix pH marker down 1.  put the two e- on the complex I card in the designated area.

* then pass an electron down the Fe-S chain, and count each time it passes an arrow.  If you have an empty CoQ (or with only one e- on it), then put the e- on it.  Otherwise the e- stops short on one of the Fe-S centers and the chain backs up.

* Do this for the second electron too.  when a CoQ has two e-, flip it over to CoQH2 and discard the e-.
   
* Then take the number of protons counted (8 total if both e- flowed completely to CoQH2) from the matrix pH and move them to your outer pH.

* return the NAD+ and the CoQH2 [to the matrix at the end of the round.]

### Complex II [ETC] [K]:
    see the dotted line dividing the reaction. 

* If the two holes in the FAD are empty, and the number of succinate in the matrix is more than the number of fumarate, turn a succinate into a fumarate.  put two electrons on the FAD.
    
* take a CoQ from the matrix and the two electrons in the FAD.  Flip the CoQ to CoQH2 and discard the electrons.

* return the CoQH2 to the matrix

### complex III [ETC]:
* take a CoQH2 from the matrix, and unload two electrons onto the chain.  flip over the CoQH2.

* take cytc from the matrix and an electron on the complex; flip over the cytc to cytc- and discard the electron.  move one from the matrix pH to your pH.

* return the cytc- to the matrix

### complex IV [ETC]:

* take a cytc- from the matrix and flip it over.  put an e- on an unoccupied
       space on the complex.  move one from the inner pH to your outer pH.
 
* when the 4 spaces are filled with e-, take an O2 from the matrix and move
       the inner pH down 4.  The O2 is now 2 water; discard it (do not return to matrix).

    return the cytc to the matrix

### ATP synthase:

* take an ADP from the matrix.
* move 4H+ from your [outer] pH to the matrix pH
* flip the ADP to ATP.

* return the ATP

### ATP translocase:

* move one H+ from your pH to the matrix pH.
* exchange an ADP in your plasm for an ATP from the matrix

### pyruvate translocase:

* take a pyruvate and 2H+ from your pool and move them to the matrix.


## Possible Game Rules

respiratory acidosis if CO2 too high.

5 RNA cards faceup in a chain.  May take as many RNA cards from the faceup
chain as desired; order must be maintained (and they are displayed in front of
them). or may take 2 cards from the facedown deck, and add them to one or more
chains (at the end).

Put the substrate cards faceup in the pool.  Put the starting number of
molecule markers on them.

Deal the protein cards out to the players faceup.

When a player has the right sequence of bases to fulfill a protein, they lay
down the protein card, discard the bases, take an ATP from their stash and flip
it to ADP.  Then they put [an additional] molecule marker on the protein card.

When all 16 cards are built, the mitochondrion divides.


# Research

http://en.wikipedia.org/wiki/ATP_synthase

Located within the mitochondria, ATP synthase consists of 2 regions
the FO portion is within the membrane.
The F1 portion of the ATP synthase is above the membrane, inside the matrix of the mitochondria.


Mitochondria structure: (1) inner membrane, (2) outer membrane, (3) cristae, (4) matrix
The nomenclature of the enzyme suffers from a long history. The F1 fraction derives its name from the term "Fraction 1" and FO (written as a subscript letter "o", not "zero") derives its name from being the oligomycin binding fraction.[1] Oligomycin, an antibiotic, is able to inhibit the FO unit of ATP synthase.
These functional regions consist of different protein subunits - refer to tables.

There are three redox states of coenzyme Q10: fully oxidized (ubiquinone), semiquinone (ubisemiquinone), and fully reduced (ubiquinol). The capacity of this molecule to exist in a completely oxidized form and a completely reduced form enables it to perform its functions in the electron transport chain and as an antioxidant respectively.

the energy in FADH2 is enough to produce 1.5 equivalents of ATP[2] by oxidative phosphorylation. Another metabolic source of FADH2 is beta oxidation, where FAD serves as a coenzyme to acyl CoA dehydrogenase.

Thermogenin (called uncoupling protein by its discoverers and now known as uncoupling protein 1, or UCP1)[1] is an uncoupling protein found in the mitochondria of brown adipose tissue (BAT). It is used to generate heat by non-shivering thermogenesis. Non-shivering thermogenesis is the primary means of heat generation in hibernating mammals and in human infants.

Carboxylic acids such as pyruvate, succinate, and citrate are transported into the matrix by the pyruvate transporter, the dicarboxylic acid transporter, and the tricarboxylic acid transporter, respectively.

Under normal conditions, ATP and ADP cannot cross the inner mitochondrial membrane due to their high negative charges, but ATP–ADP translocase, an antiporter, couples the transport of the two molecules. The depression in ATP–ADP translocase alternatively faces the matrix and the cytoplasmic sides of the membrane. ADP binding from the cytoplasm induces eversion of the transporter and results in the release of ADP into the matrix. Binding of ATP from the matrix induces eversion and results in the release of ATP into the cytoplasm and concomitantly brings the translocase back to its original conformation.[1] ATP and ADP are the only natural nucleotides recognized by the translocase.[4]

ATP-ADP exchange is energetically expensive: about 25% of the energy yielded from electron transfer by aerobic respiration, or one hydrogen ion, is consumed to regenerate the membrane potential that is tapped by ATP-ADP translocase.[1]


diseases:
  * mitochondrial myopathy
     * increased reactivity for succinate dehydrogenase and a decreased reactivity for cytochrome c oxidase
   * A3243G, the mutation for mitochondrial encephalomyopathy, lactic acidosis, and strokelike episodes
      * syndrome that most frequently consisted of hearing impairment, cognitive decline, and short stature
      * Charles Darwin

  * Acidosis refers to disorders that lower cell/tissue pH to < 7.35.

---
