# Adaptation notes

We (Oatmeal Health) have adapted this network to the 3D SSL (Self-Supervised Learning) scenario. What we discovered is that the Lung network only allows 32(H) x 192(D) x 192(W) volumes as inputs. As long as you stick to them, you should be able to use the network for both segmentation (2 output channels) and SSL (1 output channel). The batch size can be increased depending on your GPU memory.
