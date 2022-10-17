[CDDRC Docs](../README.md) - Data Access

# CDDRC Project Creation

To create a new project go to
[RedCap CDDRC project creation page](https://redcap.link/cddrc) and
fill out the form.  The tables below provide details on each of the
fields in the project creation form.

## Projects

| Field Label | Description | Becomes Mosaic Project Attribute | Required |
|-------------|-------------|----------|-------|
| Project Name | Key term[s] to describe your project.| | Yes |
| Project Description | Long form description used to record and note all necessary and desired aspects of your project. | | Yes |
| Set project privacy level to protected. | Set to `True` if you do *not* want your project publicly accessible. | | No (default: False) |
| Lab | Governing lab PI. | Yes | Yes |
| Institution | Lab and projects originating from this institution. | Yes | Yes |
| Organism | Organism under study. **[See 'Organism Table' below](#organism).** | Yes | Yes |
| Organism Name | If the above option is 'Other', specify the organism here.| | Yes* |
| Reference Genome | Organism reference genome **[See 'Reference Genome' Table below](#reference-genome)** | Yes | Yes |
| Experiment Type | Experiment methodology **[See 'Experiment Type Table' below](#experiment-type)** | Yes | Yes |
| Other Experiment Type |If the above option is 'Other', specify the type here.| | Yes* |
| Experiment Platform | Platform used to generate experiment type. **[See 'Experiment Platform Table' below](#experiment-platform)** | Yes | Yes |
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
| Manifest | Downloadable Sample Manifest template **[See 'Manifest Fields Table' below](#manifest)** | | N/A |
| Manifest Upload | Upload section for completed above manifest. | | Yes |

### <a name="organism">Organism Selector</a>

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

### <a name='reference-genome'>Reference Genome Selector</a>

| Reference Genome | Description |
|------------------|-------------|
| GRCh37 | Human build 37 |
| GRCh38 | Human build 38 |
| GRCz11 | Zebrafish build 11 |
| GRCm39 | Mouse build 39 |
| ***unsupported*** | Other builds unsupported, [contact us](mailto:cddrc@lists.utah.edu) |

### <a name='experiment-type'>Experiment Type Selector</a>

| Experiment Type             	| Description                  |
|-------------------------------|------------------------------|
| CGH                         	| [Comparative genomic hybridization](https://en.wikipedia.org/wiki/Comparative_genomic_hybridization) |
| ChiP-on-chip                	| [ChIP-on-chip](https://en.wikipedia.org/wiki/ChIP-on-chip) is a technology that combines chromatin immunoprecipitation ('ChIP') with DNA microarray ("chip"). |
| ChIP-Seq                    	|                              |
| Directional mRNA Sequencing 	|                              |
| DNA Methylation Analysis    	|                              |
| Exon                        	|                              |
| Gene Expression             	|                              |
| Genomic DNA Sequencing      	|                              |
| Hi-C                        	|                              |
| HybMap                      	|                              |
| miRNA                       	|                              |
| Mononucleosome sequencing   	|                              |
| Morpholino analysis         	|                              |
| mRNA Sequencing             	|                              |
| single cell RNA-seq         	|                              |
| Small mRNA Sequencing       	|                              |
| SNP                         	|                              | 
| Targeted Genomic Resequencing |                              |
| Transcriptome sequencing      |                              |
| ***Other***                   |                              |

### <a name='experiment-platform'>Experiment Platform Selector</a>

| Experiment Platform            |
|--------------------------------|
| Affymetrix Microarray          |
| Agilent 1-color Microarray     |
| Agilent 2-color Microarray     |
| Functional Gene Analysis       |
| Illumina HiSeq 4000 Sequencing |
| Ion Torrent                    |
| Life-SOLiD                     |
| Roche-454                      |
| ***Other***                    |


## <a name='manifest'>Manifest Fields</a>

Currently available manifest fields. 

| Manifest Column Name          | Becomes Mosaic Sample Attribute| Required | 
|-------------------------------|--------------------------------| ---------|
| Sample ID                     | Yes                            | **Yes**  |
| Individual ID                 | Yes                            | No       |
| Internal ID                   | Yes                            | No       |
| Stage                         | Yes                            | No       |
| Treatment                     | Yes                            | No       |
| Treatment Group               | Yes                            | No       |
| Gene Name                     | Yes                            | No       |
| Ensembl ID                    | Yes                            | No       |
| Molecule Type                 | Yes                            | No       |
| Sample Volume                 | Yes                            | No       |
| Organ                         | Yes                            | No       |
| Tissue                        | Yes                            | No       |
| Tissue Condition              | Yes                            | No       |
| Dose                          | Yes                            | No       |
| Genotype/Genetic Modification | Yes                            | No       |
| Phenotype                     | Yes                            | No       |
| Expression Group              | Yes                            | No       |
| Analysis Group                | Yes                            | No       |
| Replica Number                | Yes                            | No       |
| Note                          | Yes                            | No       |
