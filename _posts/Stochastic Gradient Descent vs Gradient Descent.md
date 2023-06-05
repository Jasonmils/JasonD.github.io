# Gradient descent 
**Key issue:** all the data sample from the dataset $D = \{(x_i,y_i)\}^N_{i=1}$ are used for gradient computation and update in a single iteration.  (``Batchsize`` = N)
# SGD (Mini-Batch)
**Key issue:**  Dataset $D$ is randomly shuffled and divided into mini-batches with smaller size of B rather than N. 
$$
S_j=\{(x_i,y_i)\}_{i=j}^{B+j-1}, D = S_1\bigcup S_2\bigcup \cdots\bigcup S_{N-B+1}
$$
Then, SGD conduct GD on each batch. 
# Conclusion
**Main difference:** Whether the optimization objective for each iteration is an average loss function over all samples or a loss function over a single sample.
**Main advantage of SGD or Minibatch SGD:**  It introduces stochastic noise in the iterations, making the optimizing agent easier to excape from the local optima.