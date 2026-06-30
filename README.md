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

```txt
AI\_image\_generation/
├─ anatomy/
│  └─ organ\_models/
│     ├─ anatomical\_organ\_model\_female\_silhouette\_prompt.txt
│     └─ anatomical\_organ\_model\_male\_silhouette\_prompt.txt
│
├─ pathways/
│  ├─ apoptosis/
│  │  └─ apoptosis\_pathway\_prompt.txt
│  ├─ cell\_signaling/
│  │  ├─ cell\_signaling\_pathway\_and\_gene\_activation\_prompt.txt
│  │  └─ intercellular\_signalling\_cascade\_prompt.txt
│  ├─ communication/
│  │  └─ gut\_brain\_axis/
│  │     └─ gut\_brain\_axis\_crosstalk\_prompt.txt
│  └─ gene\_regulation/
│     └─ gene\_expression\_regulation\_prompt.txt
│
├─ pathways\_additional/
│  ├─ immune\_trafficking/
│  │  └─ intestinal\_epithelium\_diapedesis/
│  │     └─ intestinal\_epithelium\_diapedesis\_prompt.txt
│  └─ tumor\_microenvironment/
│     └─ tumor\_microenvironment\_diagram\_prompt.txt
│
├─ workflows/
│  ├─ cell\_processing\_microscopy/
│  │  └─ centrifugation\_and\_microscopy\_workflow\_prompt.txt
│  ├─ lab\_workflows/
│  │  ├─ liquid\_handling\_and\_protocol\_flow\_prompt.txt
│  │  ├─ experimental\_workflow\_diagram\_prompt.txt
│  │  └─ three\_step\_workflow\_for\_cell\_lysis\_and\_rna\_extraction\_prompt.txt
│  └─ protein\_workflows/
│     ├─ four\_step\_schematic\_of\_target\_protein\_capture\_and\_elution\_prompt.txt
│     └─ protein\_handling\_and\_downstream\_assay\_prompt.txt
│
├─ techniques/
│  ├─ genome\_editing/
│  │  └─ crispr\_cas9/
│  │     └─ crispr\_cas9\_genome\_editing\_prompt.txt
│  ├─ delivery\_systems/
│  │  ├─ lipid\_nanoparticles/
│  │  │  └─ lipid\_nanoparticle\_mrna\_editing\_mechanism\_prompt.txt
│  │  └─ liposomes/
│  │     └─ liposome\_nanoparticle\_structure\_prompt.txt
│  └─ receptor\_interactions/
│     ├─ receptor\_ligand\_binding/
│     │  └─ receptor\_ligand\_binding\_prompt.txt
│     └─ transmembrane\_activation/
│        └─ transmembrane\_receptor\_activation\_prompt.txt
│
└─ templates/
   └─ three\_panel\_and\_samples/
      ├─ general\_template\_3panel\_diagram\_prompt.txt
      └─ sample\_scientific\_workflow\_with\_text\_at\_the\_bottom\_prompt.txt


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
