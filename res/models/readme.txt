Filename semantics:
<model_name>_<train_size>_<output_dim>_<selftrained_embeddings>_<num_nodes_lstm>_<num_nodes_dense>_<num_epochs>.h5

What I found:
- Sets with > ~1000 Abstracts require > 16 GB of RAM (Problematic part is one-hot Encoding of labels)
- With increasing batch sizes more memory is required (Limit reached fast when training on GPU)
