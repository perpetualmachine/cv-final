You may change the path to your data or just swith  where download=True
train_dataset = torchvision.datasets. CIFAR100(root='./data', train=True, download=False, transform=train_transform)
test_dataset = torchvision.datasets.CIFAR100(root='./data', train=False, download=False, transform=test_transform)

