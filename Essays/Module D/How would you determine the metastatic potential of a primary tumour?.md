**How would you determine the metastatic potential of a primary tumour?**

# Intro 
* Metastatic potential = tendency of a primary tumour to form a secondary tumour
* Why is it important to study this 
    * Determine what factors affect metastatic potential 
    * Different treatment modalities may be needed 
* Measure factors that have been found to be predictive of metastatic potential 
* May need a way that takes into account all factors to obtain a true predictive model – AI? 

# Methods 

## In silico 
* In silico methods
    * Sequencing and pattern analysis – are there genes that predipose a tumour to be metastatic? 
	    * Data needed – primary tumours that did not metastasise and primary tumours that did (+ when and where to)
    * Xu et al (2012) – Gene expression analyses in metastatic ovarian cells suggest that reduced stiffness may be due to actin cytoskeleton remodeling 
    * Microarray analysis (now obsolete)
        * “Using microarray gene expression patterns of breast carcinomas, Van’t Veer et al (2002) reported that a set of 117 genes predicted metastatic potential” 
        * Hoek et al (2006) – DNA microarray analyses on 86 cultures of melanoma identified three different transcriptional signatures, representing different ranges of metastatic potential. 
            * “​​TGFβ-type signalling upregulates genes expressing vasculogenic/extracellular matrix remodelling factors and Wnt signal inhibitors, coinciding with a downregulation of genes downstream of Wnt signalling” → these expression patterns can be looked for in cancers. 
    * Loss of “metastatic suppressor genes” 
    * Use AI to detect “mutational signatures” for metastatic cancers? 

## In vitro 
* In vitro methods 
    * Histopathological analysis 
        * Microscopy (ImageJ, cell profiler) 
            * Cell shape: If there is a more elongated shape, may be moving
                * Aspect ratio of length/width
                * Circularity
        * Migration speed: Can reflect metastatic potential of the cell
            * Cell tracking (using video) – may be manual or via computer vision (segmentation)
        * Wu et al (2020) –  Imaged cells using fluorescence imaging, then “measured 216 features derived from cell and nucleus morphology for more than 30,000 breast cancer cells”, then used  unsupervised clustering analysis to classify the cancer cells according to morphology and use the classes to predict metastatic potential 
    * Immunohistochemistry for cell surface markers 
    * 2D functional assays 
        * Invadopodia formation – number of cells with invadopodia, number of invadopodia per cell, area of invadopodia per cell, amount of degradation of matrix (e.g. area of matrix degraded)
            * On glass slide, add a thin gelatin matrix and add cells on top. Cancer cells will make small holes in the matrix with invadopodia. Proteins involved in invadopodia can be visualised with immunofluorescence, and points of fluorescence will overlap with the holes in the matrix.
            * HOWEVER, some normal cells can also do this, e.g. fibroblasts, endothelial cells. These are not epithelial cells though.
    * 3D functional assays  
        * See notes 
* Mass spec – proteomic comparison of metastatic vs non-metastatic tumour 

## In vivo 
* In vivo methods
    * Transplant into mouse model 
        * Ectopic transplantation
        * Orthotopic transplantation 
        * Intravital imaging combined with longitudinal studies with different tumour types in mice 
    * Identifying molecular markers 
        * immunohistochemistry (IHC), fluorescence in situ hybridization (FISH), polymerase chain reaction (PCR), and gene expression profiling
        * Overexpression of genes involved in metastasis: cell migration, invasion, angiogenesis, or epithelial-to-mesenchymal transition (EMT). This could indicate metastatic potential
            * E.g. VEGF, MMPs 
        * Measure stiffness
            * AFM microscopy – Xu et al (2012) used AFM to show that ovarian cancer cells are softer and are less stiff stiffness than normal ovarian epithelial cells. 
                * Invasive ovarian cancer cells are also more deformable tan less invasive parental cells 
            * Magnetic tweezers – Swaminathan et al (2011) used magnetic tweezers to show that tumour cells with higher stiffness have less migratory potential and are less able to invade. Stiffness can thus be used as a measure of metastatic potential 
        * Measure metabolites
            * In vivo isotope tracing analysis – Tasdogan et al (2019) used isotope tracing analysis in PDX to show that metastasizing melanomas take up more circulating lactate, as well as higher levels of MCT1 (a lactate importer) 
* Detect presence of tumour exosomes in blood (?) -> liquid biopsy 
