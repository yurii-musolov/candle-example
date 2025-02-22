[![Rust for Large Language Model Operations (LLMOps)](./resources/banner.svg)](https://www.coursera.org/learn/rust-llmops "Rust for Large Language Model Operations (LLMOps)")

# Candle Example 

Example trying to train neural network.

## Resources

[candle](https://github.com/huggingface/candle)

[safetensors](https://github.com/huggingface/safetensors)

[hf-hub](https://github.com/huggingface/hf-hub)

[Candle Documentation](https://huggingface.github.io/candle/index.html)

[Safetensors](https://huggingface.co/docs/safetensors/index)

## Running:

```sh
$ cargo run
Trying to train neural network.
Epoch:   1 Train loss:  8.38724 Test accuracy: 33.33%
Epoch:   2 Train loss:  0.78986 Test accuracy: 33.33%
Epoch:   3 Train loss:  0.69519 Test accuracy: 33.33%
Epoch:   4 Train loss:  0.69509 Test accuracy: 33.33%
Epoch:   5 Train loss:  0.69499 Test accuracy: 33.33%
Epoch:   6 Train loss:  0.69490 Test accuracy: 33.33%
Epoch:   7 Train loss:  0.69481 Test accuracy: 33.33%
Epoch:   8 Train loss:  0.69473 Test accuracy: 33.33%
Epoch:   9 Train loss:  0.69465 Test accuracy: 33.33%
Epoch:  10 Train loss:  0.69458 Test accuracy: 33.33%
Error: The model is not trained well enough.
Trying to train neural network.
Epoch:   1 Train loss: 17.94617 Test accuracy:  0.00%
Epoch:   2 Train loss:  1.11212 Test accuracy: 66.67%
Epoch:   3 Train loss:  0.90035 Test accuracy: 66.67%
Epoch:   4 Train loss:  0.84577 Test accuracy: 66.67%
Epoch:   5 Train loss:  0.82562 Test accuracy: 66.67%
Epoch:   6 Train loss:  0.81743 Test accuracy: 66.67%
Epoch:   7 Train loss:  0.80879 Test accuracy: 66.67%
Epoch:   8 Train loss:  0.79950 Test accuracy: 66.67%
Epoch:   9 Train loss:  0.78940 Test accuracy: 66.67%
Epoch:  10 Train loss:  0.77837 Test accuracy: 66.67%
Error: The model is not trained well enough.
Trying to train neural network.
Epoch:   1 Train loss:  1.52230 Test accuracy: 100.00%
real_life_votes: [13, 22]
neural_network_prediction_result: 0.0
```
