# MaBoSS : Markovian Boolean Stochastic Simulator 

MaBoSS is a C++ software for simulating continuous/discrete time Markov processes, applied on a Boolean network.

MaBoSS uses a specific language for associating transition rates to each node. Given some initial conditions, MaBoSS applies Monte-Carlo kinetic algorithm (or Gillespie algorithm) to the network to produce time trajectories. Time evolution of probabilities are estimated. In addition, global and semi-global characterizations of the whole system are computed. 

### Contact
Institut Curie 

26 rue d'Ulm 75248 PARIS CEDEX 05 

Contact: [maboss.bkmc@gmail.com](mailto://maboss.bkmc@gmail.com) 

Web Site: [https://maboss.curie.fr](https://maboss.curie.fr)

### License

The 3-Clause BSD License

### Copyright

BSD 3-Clause License (see https://opensource.org/licenses/BSD-3-Clause)  
                                                                         
Copyright (c) 2011-2020 Institut Curie, 26 rue d'Ulm, Paris, France      
All rights reserved.                                                     
                                                                         
Redistribution and use in source and binary forms, with or without       
modification, are permitted provided that the following conditions are   
met:                                                                     
                                                                         
1. Redistributions of source code must retain the above copyright notice,
this list of conditions and the following disclaimer.                    
                                                                         
2. Redistributions in binary form must reproduce the above copyright     
notice, this list of conditions and the following disclaimer in the      
documentation and/or other materials provided with the distribution.     
                                                                         
3. Neither the name of the copyright holder nor the names of its         
contributors may be used to endorse or promote products derived from this
software without specific prior written permission.                      
                                                                         
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS      
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED
TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A          
PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER
OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, 
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,      
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR       
PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF   
LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING     
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS       
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.             