# About MultiNEAT

MultiNEAT is a portable software library for performing neuroevolution, a form of machine learning that
trains neural networks with a genetic algorithm. It is based on NEAT, an advanced method for evolving
neural networks through complexification. The neural networks in NEAT begin evolution with very simple
genomes which grow over successive generations. The individuals in the evolving population are grouped
by similarity into species, and each of them can compete only with the individuals in the same species.

The combined effect of speciation, starting from the simplest initial structure and the correct
matching of the genomes through marking genes with historical markings yields an algorithm which
is proven to be very effective in many domains and benchmarks against other methods.

NEAT was developed around 2002 by Kenneth Stanley in the University of Texas at Austin.

### License

GNU Lesser General Public License v3.0 

### Documentation
[http://multineat.com/docs.html](http://multineat.com/docs.html)

### Requires

[boost](https://www.boost.org/)

### To compile

  ```bash
  python3 setup.py build_ext
  sudo python3 setup.py install
  ```
