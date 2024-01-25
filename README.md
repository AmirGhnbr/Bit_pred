# Bitcoin Future Price Prediction using improved state of art N-BEATS deep learning architecture

This is a improved TensorFlow 2 implementation of the [N-Beats paper](https://arxiv.org/abs/1905.10437)

## Requirements

- Python 3.6 or later
- TensorFlow 2.0 or later
- Yahoo Finance
- Pandas
- Numpy
- Matplotlib

## Summary

- NBeats is a state of art approach for time series forecasting using deep learning that outperforms the previous(before 2019) deep learning models.

- N-BEATS is a deep neural architecture proposed in a 2019 paper titled "N-BEATS: Neural basis expansion analysis for interpretable time series forecasting" by Boris Oreshkin, Dmitri Carpov, Nicolas Chapados, and Yoshua Bengio. The paper focuses on solving the univariate time series point forecasting problem using deep learning. The proposed architecture is based on backward and forward residual links and a very deep stack of fully-connected layers. The architecture has a generic configuration that does not employ any time-series-specific components, and it is augmented to provide outputs that are interpretable.

## Architecture

![Philnet Architecture](https://github.com/AmirGhnbr/Bit_pred/blob/main/assets/N-Beats architecture.PNG?raw=true)
