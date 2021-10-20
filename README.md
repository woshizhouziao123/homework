BL40A2010 Introduction to IoT-Based Systems
Assignment 5, 20.10.2021
Author:Zhou ZiAo
(1) Create two arrays with 10000 samples generated as Binomial random variables via Numpy similar to what we have done with Poisson random variables in the tutorial considering the following paramenters of the Binomial function:

(a) $n=100$ and $p=0.3$;

(b) $n=10000$, and $p=0.6$

Make the histogram (empirical) plots related to each vector and compare them with the analytical results with the probability distribution funtion given by:

$$\mathrm{Prob}\left[X = k \right] = \binom{n}{k}p^k(1-p)^{n-k},$$where $k$ is the number of successes in $n$ trials.

Remember to use this scipy.stats.binom in a similar way we did in the tutorial with Poisson.

![25fdd94905055c11536edfbe197da99](https://user-images.githubusercontent.com/91326706/138112459-636bd5b4-2184-4bcc-8ee7-da274dc68164.png)
![42543e2bd2a8a74bef924ebec83cd10](https://user-images.githubusercontent.com/91326706/138112482-2c188307-1508-4449-b65b-a75d248229b4.png)
![25353f0501e91d82624f7de204aa490](https://user-images.githubusercontent.com/91326706/138112493-b89258e1-52bf-448d-a958-5a6e13229286.png)
![0a7eb980f83501ffe89e39465886a02](https://user-images.githubusercontent.com/91326706/138112512-2ee4c018-0da5-4a0d-86da-e68807c06751.png)
![23e0f24120162869209c12c77d98589](https://user-images.githubusercontent.com/91326706/138112542-5586ddf5-4a87-4be0-8fae-e496a84d894e.png)
![7abf48c662c05731841cff2d0191bfb](https://user-images.githubusercontent.com/91326706/138112553-865906a3-d937-47f7-b7e0-48fadb65044b.png)
![0bb30a380e3df56fc481298ee82a29a](https://user-images.githubusercontent.com/91326706/138112615-97e786ce-af20-40b7-8c55-8b401e898bc7.png)



(2) Read Section 2.3 and Chapter 3 from Network Science and generate three different kinds of Erdos-Renyi graphs with $N=15$ (fifteen nodes) using NetworkX. The networks shall be (a) with probability $p=0.2$, (b) with probability $p=0.5$ and (c) with probability $p=0.8$. Discuss about the differences you see if these graphs represent communication networks.

![2d6ecadbaf30ffca0921441af92ba6e](https://user-images.githubusercontent.com/91326706/138112766-88062487-2514-4358-9e10-b654ac946449.png)
![55c710101ed74fc947f955000efbff2](https://user-images.githubusercontent.com/91326706/138112856-3a42166a-d777-4d55-bb9d-e6fe7b6ebfb7.png)
![b05f8b06816193e841672cff794e04a](https://user-images.githubusercontent.com/91326706/138113155-30f3bd57-6456-4d42-a35c-36e75640f6a9.png)
![eac1357384437f0102de8713a942be0](https://user-images.githubusercontent.com/91326706/138113186-17bf9bc2-7d01-45c9-bd57-9bb0a44132b9.png)
![b7f637fb1d595bc9575a1ba48fa2ddc](https://user-images.githubusercontent.com/91326706/138113193-a78ee134-294a-422b-a4a4-aee084030726.png)
![9c2f4fd0f3eecb62430e0cf3b68bf94](https://user-images.githubusercontent.com/91326706/138113210-9df8a6bc-64d4-4305-a2d4-b591fa6aaba0.png)
