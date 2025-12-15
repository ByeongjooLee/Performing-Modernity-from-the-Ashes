# Performing Modernity from the Ashes: A Network Analysis of Post-War Korean Literary Criticism (1950s-1960s)

**Keywords:** Post-war Korean Criticism, Social Network Analysis (SNA), Text Mining, Performativity, Modernity

## Abstract

This study uses Digital Humanities methodologies to analyze how Korean literary critics strategically deployed "modernity" as a discursive weapon to establish their own legitimacy and reorganize the literary order following the Korean War (1950–1953). By examining the selective reconstruction of literary history—specifically through the hierarchization of 1930s modernists Yi Sang and Kim Kirim—this research reveals how Korean critics aggressively appropriated and reshaped Western theories to navigate their specific historical trauma.

## 1. Introduction

Following the Korean War (1950–1953), the Korean literary field faced an urgent need to reconstruct its intellectual authority amidst catastrophic ruin. Traditional scholarship has often viewed the "modernity" pursued by 1950s critics as a fixed ideal to be achieved or a passive reception of Western theory. However, I argue that "modernity" was a discursive weapon strategically deployed by critics to establish their own legitimacy and reorganize the literary order.

This study uses Digital Humanities methodologies to uncover this power dynamic by analyzing how critics selectively reconstructed the literary past—specifically through the hierarchization of 1930s modernists Yi Sang and Kim Kirim. By examining this case from a non-Western, post-colonial intellectual field, I challenge the Eurocentric narrative of modernism and reveal how Korean critics aggressively appropriated and reshaped Western theories to navigate their specific historical trauma.

## 2. Methodology and Data Construction

To empirically trace the formation of critical discourse, I employed a data-driven approach combining text mining and Social Network Analysis (SNA), treating criticism as a "performative act" (Austin, Butler) that constructs the literary field.

### Data Curation
Due to the poor OCR quality of 1950s vertical, mixed-script (Korean-Chinese) archives, I manually constructed a dataset by digitizing the table of contents from major magazines (*Sasanggye*, *Hyundae Munhak*) and liberation-period journals (1945–1950), resulting in a structured corpus of over 9,800 articles.

### Text & Network Analysis
Using Python's KoNLPy (Kiwi) morphological analyzer and TF-IDF, I extracted period-specific keywords that distinguished political discourse from academic discourse. Gephi network visualization revealed the structural shift from a decentralized network in the liberation era to a centralized, hierarchical structure in the 1950s, with specific critics (e.g., Cho Yeon-hyun) occupying central hub positions.

## 3. Findings: The Politics of "Modernity"

The analysis reveals that 1950s critics performed their "modernity" by rewriting literary history to justify their own authority.

### Hierarchizing the Past
Critics (e.g., Ko Seok-gyu, Lee Eo-ryung) strategically elevated Yi Sang while marginalizing Kim Kirim. Kim Kirim was framed as a figure of "transplantation," criticized for merely importing Western techniques without internalizing them. In contrast, Yi Sang was hailed as the "transcendence of modernism" and a symbol of "existential crisis."

### Ideology of Power
This distinction was not objective but ideological. By championing Yi Sang's "internalized fracture" over Kim Kirim's "external technique," post-war critics legitimized their own focus on existential ethics and theoretical rigor (New Criticism) as the only valid form of modernity. The network analysis confirms that critics who drove this discourse effectively controlled the distribution of literary authority and silenced alternative voices.

### Public Participation
Reader submission data from the magazines reveals how the general public actively participated in shaping critical norms, demonstrating the agency of "readers" in the Global South beyond elite critical circles.

## 4. Conclusion and Poster Content

I conclude that the "modernity" of 1950s-60s Korean criticism was a performative construct achieved by selectively summoning the past from the ashes of war. This poster will present:

- **Network centrality shift diagrams** (1945-1950 vs. 1950s-1960s) showing the concentration of critical power.
- **Semantic trajectory maps** tracking the diverging discourse around Yi Sang ("existential crisis," "internalization") and Kim Kirim ("technique," "transplantation").
- **Keyword frequency visualizations** from TF-IDF analysis across *Sasanggye* and *Hyundae Munhak*.
- **Reader participation patterns** demonstrating bottom-up engagement with critical discourse.

These visualizations offer a new, data-driven perspective on how intellectual authority is constructed in times of crisis, with implications for understanding the performative nature of canon formation in post-colonial contexts.

## Bibliography

- Austin, J. L. *How to Do Things with Words*. Harvard University Press, 1975.
- Bourdieu, Pierre. *The Rules of Art: Genesis and Structure of the Literary Field*. Stanford University Press, 1996.
- Butler, Judith. *Gender Trouble*. Routledge, 1990.
- Derrida, Jacques. *Of Grammatology*. Johns Hopkins University Press, 1976.
- Foucault, Michel. *The Archaeology of Knowledge*. Vintage Books, 1982.
- Kim, Baro. "Public Data Act and Humanities Data." *Journal of Korean Classics*, vol. 57, 2022, pp. 167-192.
- Moretti, Franco. *Graphs, Maps, Trees: Abstract Models for a Literary History*. Verso, 2005.
- Yi, Jae-yon. "'Life' and 'Attitude': Machine Reading of Criticism in Kaebyok and Chosun Mundan." *Concepts and Communication*, vol. 18, 2016, pp. 5-52.

### Primary Sources
- *Sasanggye* (The World of Thought), 1953-1969.
- *Hyundae Munhak* (Modern Literature), 1955-1969.
