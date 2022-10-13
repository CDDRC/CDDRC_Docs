[CDDRC Docs](../README.md) - Data Access

# CDDRC Project Creation Documentation.

## Projects

This [link](https://redcap.link/cddrc) will take you to the current CDDRC Project creation web page.

| Field Label | Description | Becomes Mosaic Project Attribute | Required |
|-------------|-------------|----------|-------|
| Project Name | Key term[s] to describe your project.| | Yes |
| Project Description | Long form description used to record and note all necessary and desired aspects of your project. | | Yes |
| Set project privacy level to protected. | Set to `True` if you do *not* want your project publicly accessible. | | No (default: False) |
| Lab | Governing lab PI. | Yes | Yes |
| Institution | Lab and projects originating from this institution. | Yes | Yes |
| Organism | Organism under study. **See below selections.** | Yes | Yes |
| Organism Name | If the above option is 'Other', specify the organism here.| | Yes* |
| Reference Genome | Organism reference genome **See below selections.** | Yes | Yes |
| Experiment Type | Experiment methodology **See below selections.** | Yes | Yes |
| Other Experiment Type |If the above option is 'Other', specify the type here.| | Yes* |
| Experiment Platform | Platform used to generate experiment type. **See below selections.** | Yes | Yes |
| Other Experiment Platform |If the above option is 'Other', specify the type here.| | Yes* |
| Sequence Library Protocol Description | Allowed additional notes for sequence protocol. | Yes | No |
| Sequence Source | Where your project specific sequence was generated. | Yes | No |
| Genes of Interest | A **comma separated** list of specific genes of interest. | Gene Set | No |
| PCR Library Type | If any samples underwent PCR amplification | Yes | No (default: unknown) |
| Library Kit | Kits and reagents for sequencing methods. | Yes | No |
| Library Method | Library Method used in experiment. | Yes | No |
| Capture | Specific captured use in data generation.| Yes | No |
| Notes | Any additional project level notes. | Yes | No |
| Submitter First Name | First name of person submitting project request.| Yes | Yes |
| Submitter Last Name | Last name of person submitting project request.| Yes | Yes |
| Submitter Email | Email of person submitting project request.| Yes | Yes |
| Manifest | Downloadable Sample Manifest template **See below specifications.** | | N/A |
| Manifest Upload | Upload section for completed above manifest. | | Yes |

### Organism:

| Organism |
|----------------------------|
| Alligator mississippiensis |
| Anolis carolinensis |
| Celegans elegans |
| Gallus gallus |
| Human |
| Mouse |
| Rat |
| Sheep |
| Xenopus tropicalis |
| Zebrafish |
| ***Other*** |

### Reference:

| Reference Genome |
|------------------|
| GRCh37 |
| GRCh38 |
| GRCz11 |
| GRCm39. |
| ***unsupported*** |

### Experiment Type Selection:

| Experiment Type |
|-----------------|
| CGH |
| ChiP-on-chip |
| ChIP-Seq |
| Directional mRNA Sequencing |
| DNA Methylation Analysis |
| Exon |
| Gene Expression |
| Genomic DNA Sequencing |
| Hi-C |
| HybMap |
| miRNA |
| Mononucleosome sequencing |
| Morpholino analysis |
| mRNA Sequencing |
| single cell RNA-seq |
| Small mRNA Sequencing |
| SNP |
| Targeted Genomic Resequencing |
| Transcriptome sequencing |
| ***Other*** |

### Experiment Platform Selection:

| Experiment Platform |
|-----------------|
| Affymetrix Microarray |
| Agilent 1-color Microarray |
| Agilent 2-color Microarray |
| Functional Gene Analysis |
| Illumina HiSeq 4000 Sequencing |
| Ion Torrent |
| Life-SOLiD |
| Roche-454 |
| ***Other*** |


## Manifest

Currently available manifest fields. 

| Manifest Column Name | Becomes Mosaic Sample Attribute| Required | 
|----------------------|--------------------------------| ---------|
| Sample ID  | Yes | **Yes** |
| Individual ID  | Yes | No |
| Internal ID | Yes | No |
| Stage | Yes | No |
| Treatment | Yes | No |
| Treatment Group | Yes | No |
| Gene Name | Yes | No |
| Ensembl ID  | Yes | No |
| Molecule Type   | Yes | No |
| Sample Volume   | Yes |No |
| Organ   | Yes | No |
| Tissue  | Yes | No |
| Tissue Condition | Yes | No |
| Dose    | Yes | No |
| Genotype/Genetic Modification | Yes | No |
| Phenotype   | Yes | No |
| Expression Group | Yes | No |
| Analysis Group | Yes | No |
| Replica Number | Yes | No |
| Note | Yes | No |


