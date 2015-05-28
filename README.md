# Interstellar-Wormhole-Ray-Tracing
As part of a computational methods in physics class, my two team members and I created this Mathematica notebook which implements a ray tracing map for the light from a wormhole. Our approach was based on the paper by Kip Thorne et al. (http://arxiv.org/abs/1502.03809)

We have implemented parallelized and nonparallelized versions of the raytracing computation. The parallelized version leverages Mathematica's ParallelTable. To run the notebook, place files named "GargantuaSide.jpg" and "SaturnSide.jpg" in the same directory as the notebook file. These images will represent the two sides of the wormhole. To increase the accuracy of the algorithm at the cost of increased computation time, make the division size smaller in the ray-trace computation. For example, change the two instances of 512 in CreateMap to 1024.

One can use the images provided by Double Negative VFX (http://www.dneg.com/dneg_vfx/wormhole/) to render images which resemble the wormhole from Interstellar.
