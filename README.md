# rotation_projects
notebooks for working with EM data
## There are several notebooks here that introduce how to start working with our EM data. 
 1. Intro_to_python.ipynb
- How to install anaconda
- How to set up virtual environments
- Links to packages necessary for working with EM data
 2. json_management.ipynb
- A class for managing a list of json states. 
- **Important: If you load a json state and keep working in it, you need to save it again when you are finished. Use `StateManager.update_state` to do this.
 3. annotation_management.ipynb
- An outline of how to upload data to the annotation engine. API tokens come from the wiki I sent you. 
 4. MN_statebuilder_example.ipynb
- An outline of how to build custom neuroglancer states using the statebuilder.
 5. statebuilder_examples.ipynb
- Adapted from the Allen Institute. More examples for data driven state building.
 6. skeletonization.ipynb 
- Methods for skeletonization. Uses skeletor and meshparty.
 7. synapse_distributions.ipynb
- Methods for doing analyses on synapses using MeshWork
