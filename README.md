# AI_image_generation

This repository contains sample prompts for generating scientific illustrations. The generated images produced from those prompts are included as well.

## Directory structure

- `anatomy/`
  - Prompts focused on **cell/organ/organelles structures** (what the parts look like).

- `pathways/`
  - Prompts focused on **biological processes in sequence** (signaling, gene regulation, replication, etc.).

- `pathways_additional/`
  - Extra pathway-style prompts that don’t fit neatly into the main `pathways/` subfolders.

- `techniques/`
  - Prompts focused on **methods/technologies** (lab/biotech techniques like genome editing, delivery concepts, etc.).

- `workflows/`
  - Prompts focused on **step-by-step experimental or lab workflows** (what happens in order during an experiment).

- `general_templates/`
  - Reusable diagram/layout templates (e.g., 3-panel templates or sample workflow layouts) that you can adapt for new subjects.

Below is the detailed structure of the repository:

## Directory structure (clickable)

- `AI_image_generation/anatomy/`
  - `AI_image_generation/anatomy/organ_models/`
    - `AI_image_generation/anatomy/organ_models/anatomical_organ_model_female_silhouette_prompt.txt`
    - `AI_image_generation/anatomy/organ_models/anatomical_organ_model_male_silhouette_prompt.txt`

- `AI_image_generation/pathways/`
  - `AI_image_generation/pathways/apoptosis/`
    - `AI_image_generation/pathways/apoptosis/apoptosis_pathway_prompt.txt`
  - `AI_image_generation/pathways/cell_signaling/`
    - `AI_image_generation/pathways/cell_signaling/cell_signaling_pathway_and_gene_activation_prompt.txt`
    - `AI_image_generation/pathways/cell_signaling/intercellular_signalling_cascade_prompt.txt`
  - `AI_image_generation/pathways/communication/`
    - `AI_image_generation/pathways/communication/gut_brain_axis/`
      - `AI_image_generation/pathways/communication/gut_brain_axis/gut_brain_axis_crosstalk_prompt.txt`
  - `AI_image_generation/pathways/gene_regulation/`
    - `AI_image_generation/pathways/gene_regulation/gene_expression_regulation_prompt.txt`

- `AI_image_generation/pathways_additional/`
  - `AI_image_generation/pathways_additional/immune_trafficking/`
    - `AI_image_generation/pathways_additional/immune_trafficking/intestinal_epithelium_diapedesis/`
      - `AI_image_generation/pathways_additional/immune_trafficking/intestinal_epithelium_diapedesis/intestinal_epithelium_diapedesis_prompt.txt`
  - `AI_image_generation/pathways_additional/tumor_microenvironment/`
    - `AI_image_generation/pathways_additional/tumor_microenvironment/tumor_microenvironment_diagram_prompt.txt`

- `AI_image_generation/workflows/`
  - `AI_image_generation/workflows/cell_processing_microscopy/`
    - `AI_image_generation/workflows/cell_processing_microscopy/centrifugation_and_microscopy_workflow_prompt.txt`
  - `AI_image_generation/workflows/lab_workflows/`
    - `AI_image_generation/workflows/lab_workflows/liquid_handling_and_protocol_flow_prompt.txt`
    - `AI_image_generation/workflows/lab_workflows/experimental_workflow_diagram_prompt.txt`
    - `AI_image_generation/workflows/lab_workflows/three_step_workflow_for_cell_lysis_and_rna_extraction_prompt.txt`
  - `AI_image_generation/workflows/protein_workflows/`
    - `AI_image_generation/workflows/protein_workflows/four_step_schematic_of_target_protein_capture_and_elution_prompt.txt`
    - `AI_image_generation/workflows/protein_workflows/protein_handling_and_downstream_assay_prompt.txt`

- `AI_image_generation/techniques/`
  - `AI_image_generation/techniques/genome_editing/`
    - `AI_image_generation/techniques/genome_editing/crispr_cas9/`
      - `AI_image_generation/techniques/genome_editing/crispr_cas9/crispr_cas9_genome_editing_prompt.txt`
  - `AI_image_generation/techniques/delivery_systems/`
    - `AI_image_generation/techniques/delivery_systems/lipid_nanoparticles/`
      - `AI_image_generation/techniques/delivery_systems/lipid_nanoparticles/lipid_nanoparticle_mrna_editing_mechanism_prompt.txt`
    - `AI_image_generation/techniques/delivery_systems/liposomes/`
      - `AI_image_generation/techniques/delivery_systems/liposomes/liposome_nanoparticle_structure_prompt.txt`
  - `AI_image_generation/techniques/receptor_interactions/`
    - `AI_image_generation/techniques/receptor_interactions/receptor_ligand_binding/`
      - `AI_image_generation/techniques/receptor_interactions/receptor_ligand_binding/receptor_ligand_binding_prompt.txt`
    - `AI_image_generation/techniques/receptor_interactions/transmembrane_activation/`
      - `AI_image_generation/techniques/receptor_interactions/transmembrane_activation/transmembrane_receptor_activation_prompt.txt`

- `AI_image_generation/templates/`
  - `AI_image_generation/templates/three_panel_and_samples/`
    - `AI_image_generation/templates/three_panel_and_samples/general_template_3panel_diagram_prompt.txt`
    - `AI_image_generation/templates/three_panel_and_samples/sample_scientific_workflow_with_text_at_the_bottom_prompt.txt`

(Also present in the aforementioned folders are images corresponding to the prompts:)
- anatomical_organ_model_female_silhouette_prompt_image.png
- anatomical_organ_model_male_silhouette_image.png
- apoptosis_pathway_image.png
- cell_signaling_pathway_and_gene_activation_image.png
- intercellular_signalling_cascade_image.png
- gut_brain_axis_crosstalk_image.png
- gene_expression_regulation_image.png
- intestinal_epithelium_diapedesis_image.png
- tumor_microenvironment_diagram_image.png
- centrifugation_and_microscopy_workflow_image.png
- liquid_handling_and_protocol_flow_image.png
- experimental_workflow_diagram_image.png
- three_step_workflow_for_cell_lysis_and_rna_extraction_prompt.png
- four_step_schematic_of_target_protein_capture_and_elution_image.png
- protein_handling_and_downstream_assay_image.png
- crispr_cas9_genome_editing_photo.png
- lipid_nanoparticle_mrna_editing_mechanism_image.png
- liposome_nanoparticle_structure_image.png
- receptor_ligand_binding_image.png
- transmembrane_receptor_activation_image.png
- organelle_structure_mitochondrion_image.png
- protein_folding_and_chaperones_image.png
- sample_scientific_workflow_with_text_at_the_bottom_image.png


## How to use

1. Pick a prompt file from the appropriate category folder.
2. Use that prompt with your image generation model - you can paste the prompts at the following link to generate the images: https://gemini.google.com/app
3. Reference the corresponding example images included in the repo for the expected output style.

## License

CC0-1.0
