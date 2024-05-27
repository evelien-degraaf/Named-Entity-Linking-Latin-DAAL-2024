# Named-Entity-Linking-Latin-DAAL-2024

Repository for data Named Entity Linking for Latin for Data-driven Approaches to Ancient Languages (DAAL) 2024.

# Gold data

The folder Gold_data contains the following two manually annotated texts with all person entities linked to _Paulys Realencyclopädie der classischen Altertumswissenschaft_ (_RE_):
- Tacitus, _Historiae_ 1 ([LASLA edition](https://www.lasla.uliege.be/cms/c_8570411/fr/lasla-textes-latins)), every token is associated to its token and lemma URIs as found in the [LiLa Knowledge Base](https://lila-erc.eu/query/)
- Ammianus Marcellinus, _Res Gestae_ XIV ([LTA edition](https://lta.bbaw.de/text/show/24819722_ammianus_marcellinus_res_gestae)), automatically transformed from XML to CSV and appended Token_URIs
Entities were annotated and linked by Evelien de Graaf and Margherita Fantoli.

# Fuzzy matching
The Jupyter notebook contains an explanation and illustration of the Fuzzy-matching process used in the paper. The full pipeline illustration can be found below.

![NEL_pipeline_illustration](https://github.com/evelien-degraaf/Named-Entity-Linking-Latin-DAAL-2024/assets/127041405/07fdb0ce-6dd2-43ef-900f-e04acb7b1f40)
