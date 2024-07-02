# Brainstem_Dopamine_Neuron
Sleep-inducing Brainstem Dopamine neuron with random synaptic bombardment


This is an extended model of a dopamine Brainstem neuron endowed with calcium dependent mechanisms and synaptic mechanisms based on a previous description (Dougalis et al., 2017, Ionic currents influencing spontaneous firing and pacemaker frequency in dopamine neurons of the ventrolateral periaqueductal gray and dorsal raphe nucleus (vlPAG/DRN): A voltage-clamp and computational modelling study DOI: 10.1007/s10827-017-0641-0)
The model has been extended to act as an educational tool in Computational neuroscience: Internal calcium calculating mechanisms based on calcium pump extraction and calcium accumulation are available: Random membrane fluctuations due to a fuzzy backgroung glutamatergic current allow exploration of irregularity of action potential (AP) firing due to noise Synaptic mechanisms for AMPA, GABA and NMDA receptors are also available coupled to random activation of a NetCon object
________________________________________
Full control of ionic properties and synaptic properties allow full exploration of neuronal firing and its dependence on fuzzy noise, synaptic bombardment and calcium accumulation.
To run have NEURON environment installed in your pc and doubleclick the MinimalSynapticDA.hoc file: 

Depending on your distribution, you may need to recompile the .mod files as c and o files by building up the library file via mknrndll functionality
Run the mknrndll.exe (from the NEURON installation folder) and specify the model folder as the target folder in order to compile the .mod files contained therein into an nrnmech.dll library file.

