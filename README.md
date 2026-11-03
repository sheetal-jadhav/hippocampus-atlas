# Hippocampus Atlas

**An interactive atlas of the hippocampal formation: cells, layers, circuits, rhythms, function and disease, all in one page you can explore and experiment with.**

The atlas brings together anatomy, physiology, computation and clinical neuroscience of the hippocampus. Most views are live: you can inject current into model neurons, run a virtual slice experiment, break an attractor network or decode position from place cells. Every claim is tied to the primary literature.

## Views

| View | What you can explore |
|---|---|
| **Atlas** | A specimen-style map of the hippocampal formation: dentate gyrus, hilus, CA3, CA2, CA1, subiculum, pre- and parasubiculum, medial and lateral entorhinal cortex, and the alveus/fimbria. Select a region to read about it. |
| **Circuits** | The major pathways: the trisynaptic loop (perforant path → mossy fibres → Schaffer collaterals), the temporoammonic path, CA3 recurrents, the CA2 route, the return to entorhinal cortex, and septal, supramammillary and reuniens inputs. |
| **Cell types** | About 30 principal cells and interneurons (granule, mossy, pyramidal, PV basket, axo-axonic, bistratified, O-LM, CCK, ivy, neurogliaform, entorhinal stellate and more). Each card shows soma, dendrite and axon placement across layers, in the style of Klausberger & Somogyi's laminar diagrams. |
| **Firing lab** | Inject steps, ramps or hyperpolarising current into Izhikevich model neurons with an added h-current, tuned to each cell type. Watch adaptation, bursting, fast spiking, sag and rebound, compare two cells and plot f–I curves. |
| **Rhythms** | Theta with nested gamma during running, and sharp-wave ripples during rest. Simulated spike rasters show which cell types lead, follow or fall silent at each phase. |
| **Function** | Live demos of spatially tuned cells in an open arena, theta phase precession on a linear track, pattern separation in the dentate gyrus and pattern completion in CA3. Also covers the dorsal–ventral long axis. |
| **Space & time** | Functional cell types (place, time, splitter, lap, object and social cells), eight theories of hippocampal coding, and a featured walkthrough of *Space is a latent sequence* (clone-structured cognitive graphs). Includes forward and reverse replay. |
| **Plasticity** | A virtual slice experiment (HFS, theta burst, LFS and pairing, with APV, PKA-inhibitor and protein-synthesis-inhibitor conditions), STDP timing rules, the BCM sliding threshold and metaplasticity, and a region-by-region table of mechanisms. |
| **Theory & math** | Marr's three levels and three live models: Hopfield-style attractor memory with synapse loss, excitation–inhibition dynamics (rhythm vs seizure) and Bayesian decoding of position. Also an equation library and a set of key numbers. |
| **Connectivity** | A sender × receiver matrix of projections into, within and out of the hippocampal formation, shaded by strength and coloured by transmitter class. |
| **Clinical** | How the circuit fails in Alzheimer's disease, temporal lobe epilepsy and hippocampal sclerosis, global ischaemia/hypoxia, chronic stress and depression, schizophrenia, PTSD and transient global amnesia, linking each disease to model parameters. |

## Getting started

The atlas is a single, self-contained HTML file. There is nothing to install or build:

1. Download or clone this repository.
2. Open the HTML file in any modern browser.

All simulations run locally in the browser. An internet connection is only needed to load the fonts.

## Key references

The atlas cites over a hundred primary sources in context. Some of the foundations are:

- Klausberger, T., & Somogyi, P. (2008). Neuronal diversity and temporal dynamics: the unity of hippocampal circuit operations. *Science*, 321(5885), 53–57. [doi:10.1126/science.1149381](https://doi.org/10.1126/science.1149381)
- O'Keefe, J., & Dostrovsky, J. (1971). The hippocampus as a spatial map. *Brain Research*, 34(1), 171–175. [doi:10.1016/0006-8993(71)90358-1](https://doi.org/10.1016/0006-8993(71)90358-1)
- O'Keefe, J., & Recce, M. L. (1993). Phase relationship between hippocampal place units and the EEG theta rhythm. *Hippocampus*, 3(3), 317–330. [doi:10.1002/hipo.450030307](https://doi.org/10.1002/hipo.450030307)
- Marr, D. (1971). Simple memory: a theory for archicortex. *Philosophical Transactions of the Royal Society B*, 262(841), 23–81. [doi:10.1098/rstb.1971.0078](https://doi.org/10.1098/rstb.1971.0078)
- Bliss, T. V. P., & Lømo, T. (1973). Long-lasting potentiation of synaptic transmission in the dentate area of the anaesthetized rabbit following stimulation of the perforant path. *Journal of Physiology*, 232(2), 331–356. [doi:10.1113/jphysiol.1973.sp010273](https://doi.org/10.1113/jphysiol.1973.sp010273)
- Izhikevich, E. M. (2003). Simple model of spiking neurons. *IEEE Transactions on Neural Networks*, 14(6), 1569–1572. [doi:10.1109/TNN.2003.820440](https://doi.org/10.1109/TNN.2003.820440)
- Fanselow, M. S., & Dong, H.-W. (2010). Are the dorsal and ventral hippocampus functionally distinct structures? *Neuron*, 65(1), 7–19. [doi:10.1016/j.neuron.2009.11.031](https://doi.org/10.1016/j.neuron.2009.11.031)
- Raju, R. V., Guntupalli, J. S., Zhou, G., Wendelken, C., Lázaro-Gredilla, M., & George, D. (2024). Space is a latent sequence: A theory of the hippocampus. *Science Advances*, 10, eadm8470. [doi:10.1126/sciadv.adm8470](https://doi.org/10.1126/sciadv.adm8470)

## Author

**Sheetal Jadhav** · [sheetal-jadhav.github.io](https://sheetal-jadhav.github.io) · [ORCID 0000-0001-6942-7748](https://orcid.org/0000-0001-6942-7748)

Corrections and suggestions are welcome via [Issues](https://github.com/sheetal-jadhav/hippocampus-atlas/issues).
