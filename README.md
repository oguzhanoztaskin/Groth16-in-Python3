# Groth16 Implementation in Python3
Zigtur explains Groth16 very well and his current work implements Groth16 without security features and with only 
 security features, and then attempts to implement with all security features but it is not completed yet.

Here, I implement Groth16 with all security features. I attempted to closely follow the Groth16 paper and put variables in Sigma, Tau, Relation classes to show what belongs where.

If you are unfamiliar with the subject, I recommend you to first read Zigtur's work in Groth16.ipynb.

The [Groth16 paper](https://eprint.iacr.org/2016/260.pdf).

I also changed Groth16.ipynb to add some comments and fix 1-2 errors.

## Dependencies
```
pip3 install py_ecc numpy galois
```



