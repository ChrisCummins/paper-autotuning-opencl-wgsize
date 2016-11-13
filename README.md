# Autotuning OpenCL Workgroup Size for Stencil Patterns
[Chris Cummins](http://chriscummins.cc/),
[Pavlos Petoumenos](http://homepages.inf.ed.ac.uk/ppetoume/),
[Michel Steuwer](http://homepages.inf.ed.ac.uk/msteuwer/),
[Hugh Leather](http://homepages.inf.ed.ac.uk/hleather/).

**Abstract**
> Selecting an appropriate workgroup size is critical for the performance of
> OpenCL kernels, and requires knowledge of the underlying hardware, the data
> being operated on, and the implementation of the kernel. This makes portable
> performance of OpenCL programs a challenging goal, since simple heuristics and
> statically chosen values fail to exploit the available performance. To address
> this, we propose the use of machine learning-enabled autotuning to
> automatically predict workgroup sizes for stencil patterns on CPUs and multi-
> GPUs.
>
> We present three methodologies for predicting workgroup sizes. The first,
> using classifiers to select the optimal workgroup size. The second and third
> proposed methodologies employ the novel use of regressors for performing
> classification by predicting the runtime of kernels and the relative
> performance of different workgroup sizes, respectively. We evaluate the
> effectiveness of each technique in an empirical study of 429 combinations of
> architecture, kernel, and dataset, comparing an average of 629 different
> workgroup sizes for each. We find that autotuning provides a median 3.79x
> speedup over the best possible fixed workgroup size, achieving 94% of the
> maximum performance.

**Presented** The 6th International Workshop on Adaptive Self-tuning Computing
Systems. Prague, Czech Republic, Monday, Jan 18th 2016. Co-Located with HiPEAC
2016.

```
@inproceedings{cummins2016b,
    author    = "Cummins, Chris and Petoumenos, Pavlos and Steuwer, Michel and Leather, Hugh",
    title     = "Autotuning OpenCL Workgroup Size for Stencil Patterns",
    booktitle = "The 6th International Workshop on Adaptive Self-tuning Computing Systems (ADAPT)",
    arxivId   = "1511.02490v3",
    year      = "2016",
}
```