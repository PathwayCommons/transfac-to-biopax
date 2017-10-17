# transfac-to-biopax

To convert from TRANSFAC GSEA/GMT format - transcription factors and their predicted targets - to BioPAX L3.

Since July 2016, [TRANSFAC](https://en.wikipedia.org/wiki/TRANSFAC) is maintained and distributed by geneXplain GmbH, Wolfenbüttel, Germany.

See also in [this repo](https://github.com/PathwayCommons/msigdb-to-biopax) - where we converted C3 TFT subset from MSigDb to generate BioPAX sub-networks like: "Protein A (TF) controls template (gene B) reaction that leads to the RNA and then protein B". 

Here, we want to generate the same or similar BioPAX model (more detailed and, e.g., taking "+" and "-" control type into account) but this time - from the original TRANSFAC db...
