# Jenkins Pipeline Collection

This repository is a curated collection of Jenkins pipeline scripts designed to automate various stages of the software development lifecycle, including build, test, and deployment processes.&#8203;:contentReference[oaicite:0]{index=0}

---

## 📁 Repository Structure

- [script-1-basic-hello-world.txt](./script-1-basic-hello-world.txt)
- [script-2-multiple-stages.txt](./script-2-multiple-stages.txt)
- [script-3-on-a-label.txt](./script-3-on-a-label.txt)
- [script-4-parallel-stages.txt](./script-4-parallel-stages.txt)
- [script-5-seq+parallel.txt](./script-5-seq+parallel.txt)
- [script-6-execute-job.txt](./script-6-execute-job.txt)
- [script-7-node.txt](./script-7-node.txt)
- [script-8-multiplestages.txt](./script-8-multiplestages.txt)
- [script9-multiple-agents--withnode.txt](./script9-multiple-agents--withnode.txt)
- [script10-withlabel.txt](./script10-withlabel.txt)
- [script-11-params.txt](./script-11-params.txt)
- [script-12-multi-wsp-multistep.txt](./script-12-multi-wsp-multistep.txt)
- [script-13-multinode.txt](./script-13-multinode.txt)
- [multi-stage-29ex.txt](./multi-stage-29ex.txt)


---

## 🚀 Getting Started

To utilize these pipeline scripts:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/mukund-p/Jenkins_Pipeline.git
   cd Jenkins_Pipeline
   ```
2. **Set Up Jenkins**

- Ensure Jenkins is installed and running.
- Install necessary plugins, such as:
  - Pipeline
  - Git
  - GitHub Integration (if using GitHub repositories)

3. **Create a New Pipeline Job**

- In Jenkins, navigate to `New Item`.
- Enter a name for your job and select `Pipeline`.
- Under the `Pipeline` section, choose `Pipeline script` and paste the contents of the desired `.txt` file from this repository.

4. **Run the Pipeline**

- Save the job configuration.
- Click `Build Now` to execute the pipeline.
