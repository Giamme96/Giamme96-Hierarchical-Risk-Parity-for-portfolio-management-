# Hierarchical Risk Parity for portfolio management (work in progress)
This work is a part of my thesis (Ottimizzazione della gestione del portafoglio tramite tecniche di clustering gerarchico) starting with the idea of an algorithm that can automatically develops weight's for the asset composition in an arbitrary stock portfolio. The algorithm was introduced for the first time by Marcos Lopez De Prado in 2016 with "Building diversified portfolios that outperform out of sample", SSRN-id2708678. A big part of the code is referred to his work, the substantial difference is regarding the correlation matrix construction (using DCCA in thesis) and an upgrade concerning a wider option like a in-real-time stock market data(choosing a pool of assets or using random combination). 
DCCA is a method for estimating correlation matrix holding the requirement of cross-correlation between time series.
