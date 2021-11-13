# System Inspection

PDBID: 1BRS

## Tasks

- Download the pdb
- Load the system with MDTraj.
- Identify the topology and trajectory objects: coordinates, number of atoms, number of residues,
  number of chains, etc.
- View the whole pdb system with nglview.
- Identify the different molecules.
- This pdb has multiple receptor-ligand systems. Are all receptors similar? Do they have the same sequence? Are they structurally similar? Run a structural alignment or fit by hand the backbone of the common residues to get the rmsd between them (with mdtraj).
- Choose the receptor-ligand complex we are goint to work with. ¿Why did you choose those chains?

*Note*:

- ¿Did you find duplicated atoms in the pdb with alternate locations? ¿Did you know that the x-ray
  structure includes sometimes repetead atoms in a protein with different "alternate" locations? ¿Where are the alternate location indicatior and the occupancy factor in the pdb file? ¿Whats the occupancy factor?

### Useful tools

- Python, Jupyter, etc.
- NGLView
- MDTraj

### Useful sources

- https://www.rcsb.org/structure/1BRS    
- https://pdb101.rcsb.org/learn/guide-to-understanding-pdb-data/introduction    
- http://nglviewer.org/nglview/latest/    
- https://www.mdtraj.org/1.9.5/index.html  
 
Hello!
