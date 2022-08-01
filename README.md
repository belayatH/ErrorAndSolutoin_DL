# ErrorAndSolutoin_DL
1. BrokenPipeError: [Errno 32] Broken pipe, while training DL model in Pytorch
   - Set num_workers to 0 in dataloader, there is no error. e.g.,
   train_loader = DataLoader( train_ds, batch_size=8, shuffle=True, num_workers=0)
 
2. 
