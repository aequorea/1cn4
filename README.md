# 1cn4
Glycosylating erythropoetin

<p align="center">
  <img src="1cn4_gly.png" width="500"/>
</p>

Erythropoetin stimulates red blood cell production. It is used as a treatment for anemia. Potential glycosylation sites are shown in red. Predictions may be found in gly.out. This structure has three chains. It has erythropoetin bound to two copies of its receptor. Erythropoetin is chain C, so we only are interested in the predictions for chain C.

This molecule has been studied extensively in Elliott et al. (DOI 10.1074/jbc.M311095200). In all they tried close to 50 different sites for the introduction of N-linked glycosylation consensus sequences or sequons, which gives us significant data to compare predictions to. 

Experiments were performed introducting sequons at 21 of 25 positions on the C-D loop which are residues 113-137. Of these, positions 114, 115, 116, and 130 contained N-linked carbohydrate.

Between residues 113 and 137, gly21 predicts glycosylation sites at 115, 117, 134, and 137. We agree on residue 115, but we miss the sites at 114, 116, and 130. Since the paper does not say exactly which residues were tested, it's hard to say what the story is with residues 117, 134 and 137. And since residues 124 through 130 are missing from the crystal structure, it's hard to say what the story is in that range either. This is not great data for comparison between theory and experiment on random coils.

The story on alpha helices is slightly more clear. Experiments were performed introducing sequons at positions 9, 19, 55, 56, 57, 58, 69, 111, 138, 147, 144, and 155 within the alpha helices. Three of these sites at locations 55, 57, and 69 contained N-linked carbohydrate.

Gly21 predicts a total of 31 sites within the alpha helices that might be glycosylated at positions 7, 9, 11, 13, 14, 15, 16, 18, 20, 21, 22, 23, 25, 52, 53, 56, 57, 59, 69, 76, 78, 80, 82, 83, 94, 104, 106, 108, 110, 158, and 159. So out of 12 sites on which experiments were performed, gly21 incorrectly predicts 2 sites. It predicts a site at position 9 which is not glycosylated, and it does not predict a site at location 55 which is glycosylated. Other than that, predictions are consistent with the data in the 10 other cases. This is an accuracy of 83% on alpha helices.
