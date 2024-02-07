# Planning Docker Tools
This guide empowers you to harness planning algorithms provided in the `ansep/planning-tools` repository within your Docker workflows. The repository offers readily available images for several planning algorithms, including:

* SymBA* 2: A high-performance heuristic search planner.
* Complementary2: Another powerful heuristic search planner offering diverse approaches.
* ...

**Benefits:**

* **Effortless Setup:** Eliminate the need to build Docker images manually; simply pull them directly from Docker Hub.
* **Consistent Environments:** Leverage standardized environments across different setups.
* **Versatility:** Access various planning algorithms for diverse use cases.

**Getting Started:**

1. **Pull the image from Docker:**
```bash
docker pull ansep/planning-tools
```
2. **Run the planning algorithm:**
```bash
docker run -it -v YOUR_PDDL_DIR:/pddl ansep/planning-tools:ALGORITHM_NAME YOUR_DOMAIN.pddl YOUR_PROBLEM.pddl OUTPUT_PLAN.sas
```
Replace `ALGORITHM_NAME` with the specific algorithm from one of the following list, and adjust paths and filenames as needed.
