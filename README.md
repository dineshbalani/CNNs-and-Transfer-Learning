# CNNs-and-Transfer-Learning
Train an MNIST CNN classifier


Train an MNIST CNN classifier on just the digits: 1, 4, 5 and 9

    Architecture (you may change it)
    Optimizer: ADAM


Use your trained model’s weights on the lower 4 layers to train a classifier for the rest of MNIST (excluding 1,4,5 and 9)

    Create new layers for the top (5 and 6)
    Try to run as few epochs as possible to get a good classification (> 99% on test)
    Try a session with freezing the lower layers weights, and also a session of just fine-tuning the weights.

Result.pdf contains:

1. Test loss curve on MNIST-1459

2. Test loss curve on transferred MNIST-023678:
           - with fine-tuning everything
           - with frozen layers up to fc2 (and not including)
