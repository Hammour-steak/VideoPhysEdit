<h1 align="center">
  VideoPhysEdit: Physical Counterfactual Video Editing<br>
  via Rigid-Body Physical Scene Reconstruction
</h1>

<p align="center">
  <a href="https://videophysedit.github.io/"><img src="https://img.shields.io/badge/Project-Page-2563EB?style=flat&amp;logo=googlechrome&amp;logoColor=white" alt="Project Page"></a>
  <a href="https://huggingface.co/datasets/ccmoony/PCVE-RigidBench"><img src="https://img.shields.io/badge/Hugging_Face-Dataset-FFD21E?style=flat&amp;logo=huggingface&amp;logoColor=FFD21E" alt="Hugging Face Dataset"></a>
  <a href="https://github.com/Hammour-steak/PCVE-RigidBench"><img src="https://img.shields.io/badge/Benchmark-Code-181717?style=flat&amp;logo=github&amp;logoColor=white" alt="Benchmark Code"></a>
</p>

Official repository for **VideoPhysEdit**, a training-free pipeline for physical counterfactual video editing in rigid-body scenes.

Given a source video, a physical edit, and its execution frame, VideoPhysEdit generates a counterfactual video depicting the resulting motion and interactions. It reconstructs an executable physical scene that explains the observed motion, applies the edit in simulation, and uses the resulting trajectories to guide video generation. Supported edits include object insertion, object removal, and changes to physical parameters or velocity.

## Pipeline

![VideoPhysEdit pipeline: physical scene reconstruction, physical intervention, and counterfactual video generation.](assets/pipeline.png)

## Code

**Code coming soon.** We are preparing the implementation and usage instructions for release.

## Benchmark

PCVE-RigidBench provides paired source and counterfactual target videos and physical ground truth for physical counterfactual video editing. Download the dataset from [Hugging Face](https://huggingface.co/datasets/ccmoony/PCVE-RigidBench) and find the evaluation tools in the [benchmark repository](https://github.com/Hammour-steak/PCVE-RigidBench).
