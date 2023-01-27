# Sepidermidis_Analysis

Supplementary information related to publication ["Staphylococcus epidermidis RP62A’s Metabolic Network: Validation and Intervention Strategies"](https://www.mdpi.com/2218-1989/12/9/808) 
 in Metabolites.


Models:

- Sthapylococcus_epidermidis_RP62A_COBRA.xml                  Model in COBRA compatible format

- Sthapylococcus_epidermidis_RP62A_Desdoblada.xml             Decoupled model

- Sthapylococcus_epidermidis_RP62A_Biomasa_reaction.xml       Model with lumped biomass reaction

Minimal cut sets:


- essentail_reacts.txt                                        List of essential reactions

- hybridMedio.txt                                             Cut set of length 2 consisting in two exchange reactions

- hybridMedium.txt                                            List of cut sets of length 2 consisting in an exchange reactions and an internal one

# Bibtex

@article{guil2022staphylococcus,
  title={Staphylococcus epidermidis RP62A’s Metabolic Network: Validation and Intervention Strategies},
  
  author={Guil, Francisco and S{\'a}nchez-Cid, Guillermo and Garc{\'\i}a, Jos{\'e} M},
  
  journal={Metabolites},
  
  volume={12},
  
  number={9},
  
  pages={808},
  
  year={2022},
  
  abstract={Increasingly, systems biology is gaining relevance in basic and applied research. The combination of computational biology with wet laboratory methods produces synergy that results in an exponential increase in knowledge of biological systems. The study of microorganisms such as Staphylococcus epidermidis RP62A enables the researcher to understand better their metabolic networks, which allows the design of effective strategies to treat infections caused by this species or others. S. epidermidis is the second most commoncause of infection in patients with joint implants, so treating its proliferation seems vital for public health. There are different approaches to the analysis of metabolic networks. Flux balance analysis (FBA) is one of the most widespread streams of research. It allows the study of large metabolic networks, the study their structural properties, the optimization of metabolic flux, and the search for intervention strategies to modify the state of the metabolic network. This work presents the validation of the Staphylococcus epidermidis RP62A metabolic network model elaborated by Díaz Calvo et al. Then, we elaborate further on the network analysis’s essential reactions. The full set of essential reactions (including a previously unobserved one) was computed, and we classified them into equivalence classes. Some proposals to intervene in the network and design knock-outs by studying minimal cut sets of small length are also introduced. In particular, minimal cut sets related to the medium (including exchange reactions associated with medium metabolites) have been computed. In this sense, the unique external MCS (composed of cysteine and sulfate ion) has been found, and all hybrid MCS (based on knocking out both internal and exchange reactions) of length two have also been computed. The paper also points out the possible importance of these new intervention strategies.},
  
  publisher={MDPI}
}
