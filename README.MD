# Random Learning

Here are some random things I've learned that could be useful. Will update periodically

* Quaternions cannot be used for reflections only rotation use cases
* An efficient way to do matrix multiplication for Rotation Matrix `R` and list of vertices `p` is `p * R.T` instead of interating `p`  and doing `p_n * R`
* For massive objects in React better to use `useRef` and then assign state to indexed to be rendered. Will prevent a lot of state debugging later.
