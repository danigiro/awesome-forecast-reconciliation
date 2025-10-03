# Awesome Forecast Reconciliation
This repository serves as a curated reference for the domain of forecast reconciliation. It aims to contain an extensive collection of academic papers, articles, software tools, and educational resources. Ideal for researchers, analysts, and practitioners seeking to improve the consistency and precision of forecasting methodologies.

We wish to express our deep appreciation to the authors of the paper "[Forecast reconciliation: A review](https://robjhyndman.com/publications/hfreview.html)" - George Athanasopoulos, Rob J Hyndman, Nikolaos Kourentzes, and Anastasios Panagiotelis - for providing their BibTeX file, which served as the cornerstone of this repository. Their paper serves as an invaluable resource with its comprehensive and insightful analysis of the forecast reconciliation field, providing a thorough overview of the existing literature and highlighting key advancements and research trends.

The remainder of the README is organized as follows: the **Introduction** collects entry points and reviews; the three core sections cover the main reconciliation frameworks (**Cross-sectional**, **Temporal**, and **Cross-temporal**). A **Software** section catalogs open-source implementations in R and Python. **Beyond forecasting and reconciliation** gathers closely related foundations (aggregation, benchmarking, temporal distribution, accounting constraints, etc.). Finally, **Thesis** section includes dissertations in the area. 


## How to cite

If you find this repository useful in your research or applications, please cite it as:

Girolimetto, D., & Yang, YF. (2025). Awesome Forecast Reconciliation: A Curated Reference List. https://github.com/danigiro/awesome-forecast-reconciliation

```bibtex
@misc{awesomeFR,
  title        = {Awesome Forecast Reconciliation: A Curated Reference List},
  author       = {Girolimetto, Daniele and Yang, Yangzhuoran Fin},
  year         = {2025},
  url = {https://github.com/danigiro/awesome-forecast-reconciliation}
}
```


## Contents

- [Cross-sectional framework](#csframe)
- [Temporal framework](#teframe)
- [Cross-temporal framework](#ctframe)
- [Software](#soft)
- [Beyond forecasting and reconciliation](#beyond)
- [Thesis](#Thesis)

## Introduction
1. **Chapter 11 Forecasting Hierarchical and grouped time series** by Rob J Hyndman and George Athanasopoulos, _Forecasting: Principles and Practice_, 3rd edition (2021). [[url]](https://otexts.com/fpp3/hierarchical.html)
1. **Notation for forecast reconciliation** by Rob J Hyndman (2022). [[url]](https://robjhyndman.com/hyndsight/reconciliation-notation.html)
1. **Editorial: Innovations in Hierarchical Forecasting** by Athanasopoulos, George, Rob J. Hyndman, Nikolaos Kourentzes, and Anastasios Panagiotelis, _International Journal of Forecasting_ (2024). [[doi]](https://doi.org/10.1016/j.ijforecast.2024.01.003)
1. **Forecast reconciliation: A review** by Athanasopoulos, George, Rob J. Hyndman, Nikolaos Kourentzes, and Anastasios Panagiotelis, _International Journal of Forecasting_ (2024). [[doi]](https://doi.org/10.1016/j.ijforecast.2023.10.010)


## Cross-sectional framework <a name="csframe"/>
1. **Data aggregation and information loss** by Guy H. Orcutt, Harold W. Watts, John B. Edwards, _The American Economic Review_ (1968).  
1. **The Effect of Aggregation on Prediction in the Autoregressive model** by Takeshi Amemiya, Roland Y. Wu, _Journal of the American Statistical Association_ (1972). [[doi]](https://doi.org/10.1080/01621459.1972.10481264) 
1. **Top-down versus bottom-up forecasting strategies** by Albert B Schwarzkopf, Richard J Tersine, John S Morris, _International Journal of Production Research_ (1988). [[doi]](https://doi.org/10.1080/00207548808947995) 
1. **Aggregation vs disaggregation in forecasting construction activities** by Pekka Ilmakunnas, _Disaggregation in econometric modelling_ (1990).  
1. **Top-down or bottom-up: aggregate versus disaggregate extrapolations** by B J Dangerfield, J S Morris, _International Journal of Forecasting_ (1992). [[doi]](https://doi.org/10.1016/0169-2070(92)90121-O) 
1. **A simple view of top-down vs bottom-up forecasting** by L Lapide, _Journal of Business Forecasting Methods and Systems_ (1998).  
1. **An investigation of aggregate variable time series forecast strategies with specific subaggregate time series statistical correlation** by G Fliedner, _Computers and Operations Research_ (1999).  
1. **Hierarchical forecasting: issues and use guidelines** by Gene Fliedner, _Industrial Management \& Data Systems_ (2001). [[doi]](https://doi.org/10.1108/02635570110365952) 
1. **The impact of aggregation level on forecasting performance** by Giulio Zotteri, Matteo Kalchschmidt, Federico Caniato, _International Journal of Production Economics_ (2005). [[doi]](https://doi.org/10.1016/j.ijpe.2004.06.044) 
1. **A model for selecting the appropriate level of aggregation in forecasting processes** by Giulio Zotteri, Matteo Kalchschmidt, _International Journal of Production Economics_ (2007). [[doi]](https://doi.org/10.1016/j.ijpe.2006.12.030) 
1. **Top-down or bottom-up forecasting?** by Peter Wanke, Eduardo Saliby, _Pesquisa Operacional_ (2007). 
1. **Forecasting item-level demands: an analytical evaluation of top-down versus bottom-up forecasting in a production-planning framework** by H Widiarta, S Viswanathan, R Piplani, _IMA Journal of Management Mathematics_ (2008). [[doi]](https://doi.org/10.1093/imaman/dpm039) 
1. **Hierarchical estimation as a basis for hierarchical forecasting** by L W G Strijbosch, R M J Heuts, J J A Moors, _IMA Journal of Management Mathematics_ (2008). [[doi]](https://doi.org/10.1093/imaman/dpm032) 
1. **Hierarchical forecasts for Australian domestic tourism** by George Athanasopoulos, Roman A Ahmed, Rob J Hyndman, _International Journal of Forecasting_ (2009). [[doi]](https://doi.org/10.1016/j.ijforecast.2008.07.004) 
1. **Multi-horizon inflation forecasts using disaggregated data** by Carlos Capistr\a'an, Christian Constandse, Manuel Ramos-Francia, _Economic Modelling_ (2010). [[doi]](https://doi.org/10.1016/j.econmod.2010.01.006) 
1. **Top-down versus bottom-up demand forecasts: The value of shared point-of-sale data in the retail supply chain** by Brent D. Williams, Matthew A. Waller, _Journal of Business Logistics_ (2011). [[doi]](https://doi.org/10.1111/j.2158-1592.2011.01002.x) 
1. **Optimal combination forecasts for hierarchical time series** by Rob J. Hyndman, Roman A. Ahmed, George Athanasopoulos, Han Lin Shang, _Computational Statistics \& Data Analysis_ (2011). [[doi]](https://doi.org/10.1016/j.csda.2011.03.006) 
1. **Top-down strategies based on adaptive fuzzy rule-based systems for daily time series forecasting** by Ivette Luna, Rosangela Ballini, _International Journal of Forecasting_ (2011). [[doi]](https://doi.org/10.1016/j.ijforecast.2010.09.006) 
1. **The development of a hierarchical forecasting method for predicting spare parts demand in the South Korean Navy—A case study** by Seongmin Moon, Christian Hicks, Andrew Simpson, _International Journal of Production Economics_ (2012).  
1. **Sample-Based Forecasting Exploiting Hierarchical Time Series** by Ulrike Fischer, Frank Rosenthal, Wolfgang Lehner, _Proceedings of the 16th International Database Engineering Applications Sysmposium_ (2012). [[doi]](https://doi.org/10.1145/2351476.2351490) 
1. **Forecasting aggregate demand: Analytical comparison of top-down and bottom-up approaches in a multivariate exponential smoothing framework** by Giacomo Sbrana, Andrea Silvestrini, _International Journal of Production Economics_ (2013). [[doi]](https://doi.org/10.1016/j.ijpe.2013.06.022) 
1. **Aggregate vs. disaggregate forecast: Case of Hong Kong** by Shui Ki Wan, Shin Huei Wang, Chi Keung Woo, _Annals of Tourism Research_ (2013). [[doi]](https://doi.org/10.1016/j.annals.2013.03.002) 
1. **Efficient Forecasting for Hierarchical Time Series** by L Dannecker, R Lorenz, P R\osch, W Lehner, G Hackenbroich, _CIKM '13 Proceedings of the 22nd ACM international conference on Information \& Knowledge Management_ (2013). [[doi]](https://doi.org/10.1145/2505515.2505622) [[url]](http://dx.doi.org/10.1145/2505515.2505622) 
1. **Variational Bayesian inference for forecasting hierarchical time series** by Mijung Park, Marcel Nassar, _International Conference on Machine Learning, Workshop on divergence methods for probabilistic inference_ (2014). [[url]](https://privacy-preserving-machine-learning.github.io/ICMLworkshop_PARK_NASSAR.pdf) 
1. **Optimally reconciling forecasts in a hierarchy** by R J Hyndman, George Athanasopoulos, _Foresight: International Journal of Applied Forecasting_ (2014). [[url]](https://robjhyndman.com/papers/Foresight-hts-final.pdf) 
1. **Non-stationary demand forecasting by cross-sectional aggregation** by Bahman Rostami-Tabar, Mohamed Zied Babai, Yves Ducq, Aris Syntetos, _International Journal of Production Economics_ (2015).  
1. **Improving forecasts for noisy geographic time series** by S H Huddlestone, J H Porter, D E Brown, _Journal of Business Research_ (2015).  
1. **Forecast UPC-level FMCG demand, Part II: Hierarchical reconciliation** by Dazhi Yang, Gary S.W. Goh, Siwei Jiang, Allan N. Zhang, Orkan Akcan, _Proceedings - 2015 IEEE International Conference on Big Data_ (2015). [[doi]](https://doi.org/10.1109/BigData.2016.7841053) 
1. **Game-theoretically optimal reconciliation of contemporaneous hierarchical time series forecasts** by Tim van Erven, Jairo Cugliari, _Modeling and Stochastic Learning for Forecasting in High Dimension_ (2015). [[url]](https://hal.inria.fr/hal-00920559) 
1. **The sum and its parts: judgmental hierarchical forecasting** by Mirko Kremer, Enno Siemsen, Douglas J Thomas, _Management Science_ (2016). [[doi]](https://doi.org/10.1287/mnsc.2015.2259) 
1. **Hierarchical Time Series Forecast in Electrical Grids** by Vȧnia Almeida, Rita Ribeiro, Joȧo Gama, _Information Science and Applications (ICISA)_ (2016). [[doi]](https://doi.org/10.1007/978-981-10-0557-2) 
1. **Forecast UPC-level FMCG demand, Part III: Grouped reconciliation** by Dazhi Yang, Gary S.W. Goh, Siwei Jiang, Allan N. Zhang, _Proceedings - 2016 IEEE International Conference on Big Data_ (2016). [[doi]](https://doi.org/10.1109/BigData.2016.7841053) 
1. **Distributions of forecasting errors of forecast combinations: implications for inventory management** by Devon K Barrow, Nikolaos Kourentzes, _International Journal of Production Economics_ (2016).  
1. **Fast computation of reconciled forecasts for hierarchical and grouped time series** by Rob J. Hyndman, Alan J. Lee, Earo Wang, _Computational Statistics \& Data Analysis_ (2016). [[doi]](https://doi.org/10.1016/j.csda.2015.11.007) 
1. **Reconciling Forecasts of Infant Mortality Rates at National and Sub-National Levels: Grouped Time-Series Methods** by Han Lin Shang, _Population Resarch Policy Review_ (2016). [[arXiv]](http://arxiv.org/abs/1608.08718) 
1. **Grouped multivariate and functional time series forecasting: An application to annuity pricing** by Han Lin Shang, Steven Haberman, _Insurance: Mathematics and Economics_ (2017). [[doi]](https://doi.org/10.1016/j.insmatheco.2017.05.007) 
1. **Regularization in hierarchical time series forecasting with application to electricity smart meter data** by Souhaib Ben Taieb, Jiafan Yu, Mateus Neves Barreto, Ram Rajagopal, _31st AAAI Conference on Artificial Intelligence, AAAI 2017_ (2017). [[url]](https://ojs.aaai.org/index.php/AAAI/article/view/11167) 
1. **Reconciling solar forecasts: Geographical hierarchy** by Dazhi Yang, Hao Quan, Vahid R. Disfani, Licheng Liu, _Solar Energy_ (2017). [[doi]](https://doi.org/10.1016/j.solener.2017.02.010) 
1. **Aggregated moving functional median in robust prediction of hierarchical functional time series - an application to forecasting web portal users behaviors** by Daniel Kosiorowski, Dominik Mielczarek, Jerzy P. Rydlewski (2017). [[arXiv]](https://arxiv.org/abs/1710.02669) 
1. **Coherent probabilistic forecasts for hierarchical time series** by Souhaib Ben Taieb, James W. Taylor, Rob J. Hyndman, _Proceedings of the 34th International Conference on Machine Learning_ (2017). [[url]](https://proceedings.mlr.press/v70/taieb17a.html) [probabilistic] 
1. **Grouped functional time series forecasting: an application to age-specific mortality rates** by Han Lin Shang, Rob J. Hyndman, _Journal of Computational and Graphical Statistics_ (2017). [[doi]](https://doi.org/10.1080/10618600.2016.1237877) [probabilistic] 
1. **A Bayesian model for forecasting hierarchically structured time series** by Julie Novak, Scott McGarvie, Beatriz Etchegaray Garcia (2017). [[arXiv]](https://arxiv.org/abs/1711.04738) [probabilistic] 
1. **Hierarchical accounting variables forecasting by deep learning methods** by Mengke Qiao, Ke-Wei Huang, _ICIS 2018 Proceedings 7_ (2018). [[url]](https://aisel.aisnet.org/icis2018/crypto/Presentations/7) 
1. **Supply chain decision support systems based on a novel hierarchical forecasting approach** by Marco A Villegas, Diego J Pedregal, _Decision Support Systems_ (2018).  
1. **Using quadratic programming to optimally adjust hierarchical load forecasting** by Y Zhang, J Wang, T Zhao, _IEEE Transactions on Power Systems_ (2018). [[doi]](https://doi.org/10.1109/TPWRS.2018.2857628) 
1. **Generalized exponential smoothing in prediction of hierarchical time series** by Daniel Kosiorowski, Dominik Mielczarek, Jerzy Rydlewski, Ma\lgorzata Snarska, _Statistics in Transition, New series_ (2018). [[doi]](https://doi.org/10.21307/stattrans-2018-019) 
1. **Forecasting of a Hierarchical Functional Time Series on Example of Macromodel for the Day and Night Air Pollution in Silesia Region---A Critical Overview** by Daniel Kosiorowski, Dominik Mielczarek, Jerzy P. Rydlewski, _Central European Journal of Economic Modelling and Econometrics_ (2018). [[url]](https://ideas.repec.org/a/psc/journl/v10y2018i1p53-73.html) 
1. **A hierarchical approach to probabilistic wind power forecasting** by Ciaran Gilbert, Jethro Browell, David McMillan, _2018 IEEE International Conference on Probabilistic Methods Applied to Power Systems (PMAPS)_ (2018). [[doi]](https://doi.org/10.1109/PMAPS.2018.8440571) [probabilistic] 
1. **Coherent probabilistic solar power forecasting** by Hossein Panamtash, Qun Zhou, _2018 IEEE International Conference on Probabilistic Methods Applied to Power Systems (PMAPS)_ (2018). [[doi]](https://doi.org/10.1109/PMAPS.2018.8440483) [probabilistic] 
1. **Assessing the performance of hierarchical forecasting methods on the retail sector** by José Manuel Oliveira, Patrícia Ramos, _Entropy_ (2019). [[doi]](https://doi.org/10.3390/e21040436) 
1. **A self-supervised approach to hierarchical forecasting with applications to groupwise synthetic controls** by Konstantin Mishchenko, Mallory Montgomery, Federico Vaggi, _https://arxiv.org/abs/1906.10586_ (2019). 
1. **Hierarchical time series forecasting via support vector regression in the European travel retail industry** by Juan Pablo Karmy, Sebastián Maldonado, _Expert Systems with Applications_ (2019). [[doi]](https://doi.org/10.1016/j.eswa.2019.06.060) 
1. **Optimal forecast reconciliation for hierarchical and grouped time series through trace minimization** by Shanika L. Wickramasuriya, George Athanasopoulos, Rob J. Hyndman, _Journal of the American Statistical Association_ (2019). [[doi](https://doi.org/10.1080/01621459.2018.1448825)] 
1. **Machine learning applications in time series hierarchical forecasting** by Mahdi Abolghasemi, Rob J Hyndman, Garth Tarr, Christoph Bergmeir (2019). [[arXiv]](https://arxiv.org/abs/1912.00370) 
1. **Regularized regression for hierarchical forecasting without unbiasedness conditions** by Souhaib Ben Taieb, Bonsoo Koo, _Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining_ (2019). [[doi]](https://doi.org/10.1145/3292500.3330976) 
1. **Multi-task learning method for hierarchical time series forecasting** by Maoxin Yang, Qinghua Hu, Yun Wang, _Artificial Neural Networks and Machine Learning -- ICANN 2019: Text and Time Series_ (2019). [[doi]](https://doi.org/10.1007/978-3-030-30490-4_38) 
1. **Distributed Reconciliation in Day-Ahead Wind Power Forecasting** by Li Bai, Pierre Pinson, _Energies_ (2019). [[doi]](https://doi.org/10.3390/en12061112) 
1. **A bottom-up Bayesian extension for long term electricity consumption forecasting** by F L C da Silva, F L Cyrino Oliveira, R C Souza, _Energy_ (2019). [[doi]](https://doi.org/10.1016/j.energy.2018.10.201) [[url]](http://dx.doi.org/10.1016/j.energy.2018.10.201) 
1. **A forecast reconciliation approach to cause-of-death mortality modeling** by Han Li, Hong Li, Yang Lu, Anastasios Panagiotelis, _Insurance: Mathematics and Economics_ (2019).  
1. **Analyzing mortality bond indexes via hierarchical forecast reconciliation** by Han Li, Qihe Tang, _ASTIN Bulletin_ (2019). [[doi]](https://doi.org/10.1017/asb.2019.19) 
1. **Day-ahead hierarchical probabilistic load forecasting with linear quantile regression and empirical copulas** by Tianhui Zhao, Jianxue Wang, Yao Zhang, _IEEE Access_ (2019). [[doi]](https://doi.org/10.1109/ACCESS.2019.2922744) [probabilistic] 
1. **Global energy forecasting competition 2017: Hierarchical probabilistic load forecasting** by Tao Hong, Jingrui Xie, Jonathan Black, _International Journal of Forecasting_ (2019). [[doi]](https://doi.org/10.1016/j.ijforecast.2019.02.006) [probabilistic] 
1. **Reconciled boosted models for GEFCom2017 hierarchical probabilistic load forecasting** by Cameron Roach, _International Journal of Forecasting_ (2019). [[doi]](https://doi.org/10.1016/j.ijforecast.2018.09.009) [probabilistic] 
1. **Prediction of hierarchical time series using structured regularization and its application to artificial neural networks** by Tomokaze Shiratori, Ken Kobayashi, Yuichi Takano, _PLOS ONE_ (2020). [[doi]](https://doi.org/10.1371/journal.pone.0242099) 
1. **Hierarchical forecasting** by George Athanasopoulos, Puwasala Gamakumara, Anastasios Panagiotelis, Rob J Hyndman, Mohamed Affan, _Macroeconomic Forecasting in the Era of Big Data_ (2020). [[doi]](https://doi.org/10.1007/978-3-030-31150-6_21) 
1. **Optimal non-negative forecast reconciliation** by Shanika L. Wickramasuriya, Berwin A. Turlach, Rob J. Hyndman, _Statistics and Computing_ (2020). [[doi]](https://doi.org/10.1007/s11222-020-09930-0) 
1. **Forecasting hierarchical time series with a regularized embedding space** by Jeffrey L. Gleason, _MileTS '20: 6th KDD Workshop on Mining and Learning from Time Series 2020_ (2020). [[url]](https://kdd-milets.github.io/milets2020/papers/MiLeTS2020_paper_13.pdf) 
1. **Fully reconciled GDP forecasts from income and expenditure sides** by Luisa Bisaglia, Tommaso Di Fonzo, Daniele Girolimetto, _Book of Short Papers SIS 2020_ (2020). [[arXiv]](https://arxiv.org/abs/2004.03864)
1. **Forecasting of cohort fertility under a hierarchical Bayesian approach** by Joanne Ellison, Erengul Dodd, Jonathan J Forster, _Journal of the Royal Statistical Society, Series A,_ (2020). [[doi]](https://doi.org/10.1111/rssa.12566) 
1. **Hierarchical demand forecasting benchmark for the distribution grid** by Lorenzo Nespoli, Vasco Medici, Kristijan Lopatichki, Fabrizio Sossan, _Electric Power Systems Research_ (2020). [[doi]](https://doi.org/10.1016/j.epsr.2020.106755) 
1. **Reconciling solar forecasts: Probabilistic forecasting with homoscedastic Gaussian errors on a geographical hierarchy** by Gokhan Mert Yagli, Dazhi Yang, Dipti Srinivasan, _Solar Energy_ (2020). [[doi]](https://doi.org/10.1016/j.solener.2020.06.005) [probabilistic] 
1. **Reconciling solar forecasts: Probabilistic forecast reconciliation in a nonparametric framework** by Dazhi Yang, _Solar Energy_ (2020). [[doi]](https://doi.org/10.1016/j.solener.2020.03.095) [probabilistic] 
1. **Stochastic coherency in forecast reconciliation** by Kandrika F. Pritularga, Ivan Svetunkov, Nikolaos Kourentzes, _International Journal of Production Economics_ (2021). [[doi]](https://doi.org/10.1016/j.ijpe.2021.108221) 
1. **Deep LSTM-based transfer learning approach for coherent forecasts in hierarchical time series** by Alaa Sagheer, Hala Hamdoun, Hassan Youness, _Sensors_ (2021).  
1. **Assessing mortality inequality in the U.S.: What can be said about the future?** by Han Li, Rob J. Hyndman, _Insurance: Mathematics and Economics_ (2021). [[doi]](https://doi.org/10.1016/j.insmatheco.2021.03.014) 
1. **Visitor arrivals forecasts amid COVID-19: A perspective from the Africa team** by Nikolaos Kourentzes, Andrea Saayman, Philippe Jean-Pierre, Davide Provenzano, Mondher Sahli, Neelu Seetaram, Serena Volo, _Annals of Tourism Research_ (2021).  
1. **Forecast reconciliation: A geometric view with new insights on bias correction** by Anastasios Panagiotelis, George Athanasopoulos, Puwasala Gamakumara, Rob J. Hyndman, _International Journal of Forecasting_ (2021). [[doi]](https://doi.org/10.1016/j.ijforecast.2020.06.004) 
1. **Properties of point forecast reconciliation approaches** by Shanika L Wickramasuriya (2021). [[arXiv]](https://arxiv.org/abs/2103.11129) 
1. **Forecasting Swiss exports using Bayesian forecast reconciliation** by Florian Eckert, Rob J. Hyndman, Anastasios Panagiotelis, _European Journal of Operational Research_ (2021). [[doi]](https://doi.org/10.1016/j.ejor.2020.09.046) 
1. **A trainable reconciliation method for hierarchical time-series** by Davide Burba, Trista Chen (2021). [[arXiv]](https://arxiv.org/abs/2101.01329) 
1. **Understanding forecast reconciliation** by Ross Hollyman, Fotios Petropoulos, Michael E. Tipping, _European Journal of Operational Research_ (2021). [[doi]](https://doi.org/10.1016/j.ejor.2021.01.017) 
1. **A machine learning approach for forecasting hierarchical time series** by Paolo Mancuso, Veronica Piccialli, Antonio M. Sudoso, _Expert Systems with Applications_ (2021). [[doi]](https://doi.org/10.1016/j.eswa.2021.115102) 
1. **Hierarchical probabilistic forecasting of electricity demand with smart meter data** by Souhaib Ben Taieb, James W. Taylor, Rob J. Hyndman, _Journal of the American Statistical Association_ (2021). [[doi]](https://doi.org/10.1080/01621459.2020.1736081) [probabilistic] 
1. **Improving Probabilistic Infectious Disease Forecasting Through Coherence** by G C Gibson, K R Moran, N G Reich, D Osthus, _PLoS computational biology_ (2021). [[doi]](https://doi.org/10.1371/journal.pcbi.1007623) [[url]](http://dx.doi.org/10.1371/journal.pcbi.1007623) [probabilistic] 
1. **End-to-end learning of coherent probabilistic forecasts for hierarchical time series** by Syama Sundar Rangapuram, Lucien D Werner, Konstantinos Benidis, Pedro Mercado, Jan Gasthaus, Tim Januschowski, _Proceedings of the 38th International Conference on Machine Learning, PMLR 139_ (2021). [[url]](http://proceedings.mlr.press/v139/rangapuram21a.html)
    - See [Software](#soft) for the implementation in the `GluonTS` package. [probabilistic] 
1. **Probabilistic reconciliation of hierarchical forecast via Bayes' rule** by Giorgio Corani, Dario Azzimonti, Jo\~ao P. S. C. Augusto, Marco Zaffalon, _Machine Learning and Knowledge Discovery in Databases_ (2021). [[doi]](https://doi.org/10.1007/978-3-030-67664-3_13) [probabilistic] 
1. **An ensemble methodology for hierarchical probabilistic electric vehicle load forecasting at regular charging stations** by L Buzna, P De Falco, G Ferruzzi, S Khormali, D Proto, N Refa, M Straka, G van der Poele, _Applied energy_ (2021). [[doi]](https://doi.org/10.1016/j.apenergy.2020.116337) [[url]](http://dx.doi.org/10.1016/j.apenergy.2020.116337) [probabilistic] 
1. **Probabilistic Gradient Boosting Machines for Large-Scale Probabilistic Regression** by Olivier Sprangers, Sebastian Schelter, Maarten de Rijke, _Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining_ (2021). [[doi]](https://doi.org/10.1145/3447548.3467278) [probabilistic] 
1. **Simultaneously reconciled quantile forecasting of hierarchically related time series** by Xing Han, Sambarta Dasgupta, Joydeep Ghosh, _Proceedings of the 24th International Conference on Artificial Intelligence and Statistics (AISTATS)_ (2021). [[arXiv]](https://arxiv.org/abs/2102.12612) [probabilistic] 
1. **Automatic hierarchical time-series forecasting using Gaussian processes** by Luis Roque, Luis Torgo, Carlos Soares, _Engineering Proceedings_ (2021). [[doi]](https://doi.org/10.3390/engproc2021005049) [probabilistic] 
1. **Hierarchically regularized deep forecasting** by Biswajit Paria, Rajat Sen, Amr Ahmed, Abhimanyu Das (2021). [[arXiv]](https://arxiv.org/abs/2106.07630) [probabilistic] 
1. **End-to-End Modeling Hierarchical Time Series Using Autoregressive Transformer and Conditional Normalizing Flow based Reconciliation** by Shiyu Wang, Fan Zhou, Yinbo Sun, Lintao Ma, James Zhang, Yangfei Zheng, Lei Lei, Yun Hu, _2022 IEEE International Conference on Data Mining Workshops_ (2022). [[arXiv]](https://arxiv.org/abs/2212.13706)  
1. **Using stochastic hierarchical aggregation constraints to nowcast regional economic aggregates** by Gary Koop, Stuart Mcintyre, James Mitchell, Aubrey Poon, _International Journal of Forecasting_ (2022). [[url]](http://escoe-website.s3.amazonaws.com/wp-content/uploads/2022/03/03155343/ESCoE-DP-2022-04.pdf) 
1. **Fast forecast reconciliation using linear models** by Mahsa Ashouri, Rob J. Hyndman, Galit Shmueli, _Journal of Computational \& Graphical Statistics_ (2022). [[doi]](https://doi.org/10.1080/10618600.2021.1939038) 
1. **Forecast combination-based forecast reconciliation: Insights and extensions** by Tommaso Di Fonzo, Daniele Girolimetto, _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2022.07.001) [[arXiv]](https://arxiv.org/abs/2006.08570) 
1. **Machine learning applications in hierarchical time series forecasting: Investigating the impact of promotions** by Mahdi Abolghasemi, Garth Tarr, Christoph Bergmeir, _International Journal of Forecasting_ (2022).  
1. **Model selection in reconciling hierarchical time series** by Mahdi Abolghasemi, Rob J Hyndman, Evangelos Spiliotis, Christoph Bergmeir, _Machine Learning_ (2022). [[doi]](https://doi.org/10.1007/s10994-021-06126-z) 
1. **Hierarchical forecasting with a top-down alignment of independent level forecasts** by Matthias Anderer, Feng Li, _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2021.12.015) 
1. **Hierarchical Forecasting for Aggregated Curves with an Application to Day-Ahead Electricity Price Auctions.** by Ghelasi, Paul, and Florian Ziel _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2022.11.004) 
1. **Hierarchical Mortality Forecasting with EVT Tails: An Application to Solvency Capital Requirement.**, by Li, Han, and Hua Chen, _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2022.08.007) 
1. **Forecasting Australian Fertility by Age, Region, and Birthplace.** by Yang, Yang, Han Lin Shang, and James Raymer, _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2022.08.001) 
1. **Online hierarchical forecasting for power consumption data** by Margaux Brégėre, Malo Huard, _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2021.05.011) 
1. **Forecasting unemployment in Brazil: A robust reconciliation approach using hierarchical data** by Maurício Franca Lila, Erick Meira, Fernando Luiz Cyrino Oliveira, _Socio-Economic Planning Sciences_ (2022). [[doi]](https://doi.org/10.1016/j.seps.2022.101298) 
1. **Forecasting hierarchical time series in supply chains: an empirical investigation** by Dejan Mircetic, Bahman Rostami-Tabar, Svetlana Nikolicic, Marinko Maslaric, _International Journal of Production Research_ (2022). [[doi]](https://doi.org/10.1080/00207543.2021.1896817) 
1. **Fully reconciled probabilistic GDP forecasts from income and expenditure sides** by Tommaso Di Fonzo, Daniele Girolimetto, _Book of Short Papers SIS 2022_ (2022). [[url]](https://it.pearson.com/content/dam/region-core/italy/pearson-italy/pdf/Docenti/Universit%C3%A0/Sis-2022-4c-low.pdf) [[arXiv]](https://arxiv.org/abs/2004.03864) [probabilistic] 
1. **Probabilistic reconciliation of count time series** by Giorgio Corani, Dario Azzimonti, Nicolo Rubattu (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2023.04.003) [[arXiv]](https://arxiv.org/abs/2207.09322) [probabilistic] 
1. **Probabilistic hierarchical forecasting with deep Poisson mixtures** by Kin G Olivares, O Nganba Meetei, Ruijun Ma, Rohan Reddy, Mengfei Cao, Lee Dicker (2022). [[arXiv]](https://arxiv.org/abs/2110.13179v6) [probabilistic] 
1. **Blending gradient boosted trees and neural networks for point and probabilistic forecasting of hierarchical time series** by Ioannis Nasios, Konstantinos Vogklis, _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2022.01.001) [probabilistic] 
1. **A hybrid approach with step-size aggregation to forecasting hierarchical time series** by Hakeem-Ur- Rehman, Guohua Wan, Raza Rafique, _Journal of forecasting_ (2023). [[doi]](https://doi.org/10.1002/for.2895) [[url]](http://dx.doi.org/10.1002/for.2895) 
1. **Pooling information across levels in hierarchical time series forecasting via kernel methods** by Juan Pablo Karmy, Julio López, Sebastián Maldonado, _Expert Systems with Applications_ (2023). [[doi]](https://doi.org/10.1016/j.eswa.2022.118830) 
1. **On the evaluation of hierarchical forecasts** by G. Athanasopoulos, N. Kourentzes, _International Journal of Forecasting_ (2023).  
1. **Optimal reconciliation with immutable forecasts** by Bohan Zhang, Yanfei Kang, Anastasios Panagiotelis, Feng Li, _European Journal of Operational Research_ (2023). [[doi]](https://doi.org/10.1016/j.ejor.2022.11.035) 
1. **Hierarchical Transfer Learning with Applications to Electricity Load Forecasting.** by Antoniadis, Anestis, Solenne Gaucher, and Yannig Goude, _International Journal of Forecasting_ (2023). [[doi]](https://doi.org/10.1016/j.ijforecast.2023.04.006) 
1. **Optimal Hierarchical EWMA Forecasting.** by Sbrana, Giacomo, and Matteo Pelagatti, _International Journal of Forecasting_ (2023). [[doi]](https://doi.org/10.1016/j.ijforecast.2022.12.008) 
1. **Reconciliation of wind power forecasts in spatial hierarchies** by Mads E Hansen, Nystrup Peter, Jan K M\oller, Madsen Henrik, _Wind Energy_ (2023).  
1. **Probabilistic forecast reconciliation: properties, evaluation and score optimisation** by Anastasios Panagiotelis, Puwasala Gamakumara, George Athanasopoulos, Rob J Hyndman, _European Journal of Operational Research_ (2023). [[doi]](https://doi.org/10.1016/j.ejor.2022.07.040) [probabilistic] 
1. **Dirichlet Proportions Model for Hierarchically Coherent Probabilistic Forecasting** by Abhimanyu Das, Weihao Kong, Biswajit Paria, Rajat Sen (2023). [[doi]](https://doi.org/10.48550/ARXIV.2204.10414) [[arXiv]](https://arxiv.org/abs/2204.10414) [probabilistic] 
1. **Probabilistic Forecast Reconciliation under the Gaussian Framework** by Shanika L. Wickramasuriya, _Journal of Business and Economic Statistics_ (2023). [[doi]](https://doi.org/10.1080/07350015.2023.2181176) [[url]](https://doi.org/10.1080/07350015.2023.2181176) [[arXiv]](https://arxiv.org/abs/2103.11128) [probabilistic] 
1. **Probabilistic forecasts using expert judgement: the road to recovery from COVID-19** by G Athanasopoulos, R J Hyndman, N Kourentzes, M. O'Hara-Wild, _Journal of Travel Research_ (2023). [[doi]](https://doi.org/10.1177/00472875211059240) [probabilistic] 
1. **Do we want coherent hierarchical forecasts, or minimal MAPEs or MAEs? (We won't get both!)** by Stephan Kolassa, _International Journal of Forecasting_ (2023). [probabilistic] 
1. **Point and probabilistic forecast reconciliation for general linearly constrained multiple time series** by Daniele Girolimetto, Tommaso Di Fonzo, _Statistical Methods & Applications_ (2023). [[doi]](https://doi.org/10.1007/s10260-023-00738-6) [[github]](https://github.com/danigiro/mtsreco) [[arXiv]](https://arxiv.org/abs/2305.05330) [probabilistic] 
1. **Coherent Hierarchical Probabilistic Forecasting of Electric Vehicle Charging Demand** by Zheng, Kedi, Hanwei Xu, Zeyang Long, Yi Wang, and Qixin Chen, _IEEE Transactions on Industry Applications_ (2023). [[doi]](https://doi.org/10.1109/tia.2023.3344544) [probabilistic] 
1. **Multivariate Online Linear Regression for Hierarchical Forecasting.** by Hihat, Massil, Guillaume Garrigos, Adeline Fermanian, and Simon Bussy (2024). [[arXiv]](http://arxiv.org/abs/2402.14578) 
1. **Improving out-of-sample forecasts of stock price indexes with forecast reconciliation and clustering.** by Raffaele Mattera, George Athanasopoulos, Rob J. Hyndman _Quantitative Finance_ (2024) [[doi]](https://doi.org/10.1080/14697688.2024.2412687) [[github]](http://github.com/raffmattera/stockprices_reco)
1. **Forecast Linear Augmented Projection (FLAP): A free lunch to reduce forecast error variance.** Yangzhuoran Fin Yang, George Athanasopoulos, Rob J Hyndman, Anastasios Panagiotelis (2024). [[arXiv]](https://arxiv.org/abs/2407.01868) [[github]](http://github.com/FinYang/paper-forecast-projection)
1. **Exploiting intraday decompositions in Realized Volatility forecasting: a forecast reconciliation approach.** Massimiliano Caporin, Tommaso Di Fonzo, Daniele Girolimetto, _Journal of Financial Econometrics_ (2024). [[doi]](https://doi.org/10.1093/jjfinec/nbae014) [[arXiv]](https://arxiv.org/abs/2306.02952)
1. **Coherent forecast combination for linearly constrained multiple time series.** by Daniele Girolimetto, Tommaso Di Fonzo, (2024). [[arXiv]](https://arxiv.org/abs/2412.03429)
1. **Optimal Forecast Reconciliation with Time Series Selection.** by Wang, Xiaoqian, Rob J. Hyndman, and Shanika L. Wickramasuriya, _European J Operational Research_ (2025). [[doi]](https://doi.org/10.1016/j.ejor.2024.12.004) [[url]](https://robjhyndman.com/publications/hf_selection.html) [[github]](http://github.com/xqnwang/hfs)

## Temporal framework <a name="teframe"/>
1. **Forecasting with temporal hierarchies** by George Athanasopoulos, Rob J. Hyndman, Nikolaos Kourentzes, Fotios Petropoulos, _European Journal of Operational Research_ (2017). [[doi]](https://doi.org/10.1016/j.ejor.2017.02.046)
1. **Reconciling solar forecasts: Temporal hierarchy** by Dazhi Yang, Hao Quan, Vahid R. Disfani, Carlos D. Rodríguez-Gallegos, _Solar Energy_ (2017). [[doi]](https://doi.org/10.1016/j.solener.2017.09.055)
1. **Improving the forecasting performance of temporal hierarchies** by Evangelos Spiliotis, Fotios Petropoulos, Vassilios Assimakopoulos, _PLoS ONE_ (2019). [[doi]](https://doi.org/10.1371/journal.pone.0223422)
1. **Probabilistic forecast reconciliation with applications to wind power and electric load** by Jooyoung Jeon, Anastasios Panagiotelis, Fotios Petropoulos, _European Journal of Operational Research_ (2019). [[doi]](https://doi.org/10.1016/j.ejor.2019.05.020) [probabilistic]
1. **Temporal hierarchies with autocorrelation for load forecasting** by Peter Nystrup, Erik Lindstr\om, Pierre Pinson, Henrik Madsen, _European Journal of Operational Research_ (2020). [[doi]](https://doi.org/10.1016/j.ejor.2019.07.061)
1. **Heat load forecasting using adaptive temporal hierarchies** by Hj\orleifur G. Bergsteinsson, Jan Kloppenborg M\oller, Peter Nystrup, \'Olafur Pétur Pálsson, Daniela Guericke, Henrik Madsen, _Applied Energy_ (2021). [[doi]](https://doi.org/10.1016/j.apenergy.2021.116872)
1. **Dimensionality reduction in forecasting with temporal hierarchies** by Peter Nystrup, Erik Lindstr\om, Jan K. M\oller, Henrik Madsen, _International Journal of Forecasting_ (2021). [[doi]](https://doi.org/10.1016/j.ijforecast.2020.12.003)
1. **Hierarchical forecast reconciliation with machine learning** by Evangelos Spiliotis, Mahdi Abolghasemi, Rob J Hyndman, Fotios Petropoulos, Vassilios Assimakopoulos, _Applied Soft Computing_ (2021). 
1. **Forecasting with deep temporal hierarchies** by Filotas Theodosiou, Nikolaos Kourentzes, _Available at SSRN 3918315_ (2021). 
1. **Deep Learning Temporal Hierarchies for Interval Forecasts** by Filotas Theodosiou, Nikolaos Kourentzes (2021). [[url]](https://www.researchgate.net/publication/358425154_Deep_Learning_Temporal_Hierarchies_for_Interval_Forecasts) [probabilistic]
1. **Temporal Hierarchical Reconciliation for Consistent Water Resources Forecasting Across Multiple Timescales: An Application to Precipitation Forecasting** by M S Jahangir, J Quilty, _Water resources research_ (2022). [[doi]](https://doi.org/10.1029/2021WR031862) [[url]](http://dx.doi.org/10.1029/2021WR031862)
1. **Dynamic Temporal Reconciliation by Reinforcement learning** by Himanshi Charotia, Abhishek Garg, Gaurav Dhama, Naman Maheshwari (2022). [[arXiv]](https://arxiv.org/abs/2201.11964)
1. **Efficient probabilistic reconciliation of forecasts for real-valued and count time series** by Lorenzo Zambon, Dario Azzimonti, Giorgio Corani, _Statistics and Computing_ (2022). [[doi]](https://doi.org/10.1007/s11222-023-10343-y) [[arXiv]](https://arxiv.org/abs/2210.02286) [probabilistic]
1. **Likelihood-Based Inference in Temporal Hierarchies.** by Møller, Jan Kloppenborg, Peter Nystrup, and Henrik Madsen, _International Journal of Forecasting_ (2023). [[doi]](https://doi.org/10.1016/j.ijforecast.2022.12.005)
1. **Reconciling Temporal Hierarchies of Wind Power Production with Forecast-Dependent Variance Structures** by Sørensen, Mikkel L., Jan K. Møller, and Henrik Madsen, _European Mathematical Society Magazine_ (2023). [[doi]](https://doi.org/10.4171/mag/172)
1. **Forecast reconciliation in the temporal hierarchy: Special case of intermittent demand with obsolescence** by Kamal Sanguri, Sabyasachi Patra, Sushil Punia, _Expert Systems with Applications_ (2023) [[doi]]](https://doi.org/10.1016/j.eswa.2023.119566)
1. **Check for Updates Electricity Load and Peak Forecasting: Feature Engineering, Probabilistic Light GBM and Temporal Hierarchies** by Rubattu, Nicolò, Gabriele Maroni, and Giorgio Corani, _Advanced Analytics and Learning on Temporal Data: 8th ECML PKDD Workshop_ (2023). [probabilistic]
1. **Optimal Forecast Reconciliation with Uncertainty Quantification.** by Møller, Jan Kloppenborg, Peter Nystrup, Poul G. Hjorth, and Henrik Madsen (2024). [[arXiv]](http://arxiv.org/abs/2402.06480)
1. **Optimal Reconciliation of Hierarchical Wind Energy Forecasts Utilizing Temporal Correlation.** by Navneet Sharma, Rohit Bhakar, and Prerna Jain, _Energy Conversion and Management_ (2024). [[doi]](https://doi.org/10.1016/j.enconman.2023.118053)



## Cross-temporal framework <a name="ctframe"/>
1. **A greedy aggregation–decomposition method for intermittent demand forecasting in fashion retailing** by Chongshou Li, Andrew Lim, _European Journal of Operational Research_ (2018). [[doi]](https://doi.org/10.1016/j.ejor.2018.02.029)
1. **Cross-temporal coherent forecasts for Australian tourism** by Nikolaos Kourentzes, George Athanasopoulos, _Annals of Tourism Research_ (2019). [[doi]](https://doi.org/10.1016/j.annals.2019.02.001)
1. **Reconciling solar forecasts: Sequential reconciliation** by Gokhan Mert Yagli, Dazhi Yang, Dipti Srinivasan, _Solar Energy_ (2019). [[doi]](https://doi.org/10.1016/j.solener.2018.12.075)
1. **A cross-temporal hierarchical framework and deep learning for supply chain forecasting** by Sushil Punia, Surya P. Singh, Jitendra K. Madaan, _Computers \& Industrial Engineering_ (2020). [[doi]](https://doi.org/10.1016/j.cie.2020.106796)
1. **Cross-temporal aggregation: Improving the forecast accuracy of hierarchical electricity consumption** by Evangelos Spiliotis, Fotios Petropoulos, Nikolaos Kourentzes, Vassilios Assimakopoulos, _Applied Energy_ (2020). [[doi]](https://doi.org/10.1016/j.apenergy.2019.114339)
1. **Enhancements in cross-temporal forecast reconciliation, with an application to solar irradiance forecasts** by Tommaso Di Fonzo, Daniele Girolimetto (2022). [[arXiv]](https://arxiv.org/abs/2209.07146)
1. **Toward a one-number forecast: cross-temporal hierarchies** by Nikolaos Kourentzes, _Foresight: The International Journal of Applied Forecasting_ (2022). 
1. **Cross-temporal forecast reconciliation: Optimal combination method and heuristic alternatives** by Tommaso Di Fonzo, Daniele Girolimetto, _International Journal of Forecasting_ (2023). [[doi]](https://doi.org/10.1016/j.ijforecast.2021.08.004) [[github]](https://github.com/danigiro/AusGDP_IJF) [[arXiv]](https://arxiv.org/abs/2303.17277)
1. **Spatio-temporal reconciliation of solar forecasts** by Tommaso Di Fonzo, Daniele Girolimetto, _Solar Energy_ (2023). 
1. **A novel reconciliation approach for hierarchical electricity consumption forecasting based on resistant regression** by Erick Meira, Maur\'\icio Franca Lila, Fernando Luiz Cyrino Oliveira, _Energy_ (2023). [[doi]](https://doi.org/10.1016/j.energy.2023.126794) [probabilistic]
1. **Cross-temporal Probabilistic Forecast Reconciliation** by Daniele Girolimetto, George Athanasopoulos, Tommaso  Di Fonzo, Rob J Hyndman, _International Journal of Forecasting_ (2024). [[doi]](https://doi.org/10.1016/j.ijforecast.2023.10.003) [[github]](https://github.com/danigiro/ctprob) [[arXiv]](https://arxiv.org/abs/2303.17277) [probabilistic]

## Software <a name="soft"/>
### R
1. **gtop: Game-Theoretically OPtimal (GTOP) Reconciliation Method** by Jairo Cugliari, Tim van Erven (2015). [[R archive]](https://cran.r-project.org/src/contrib/Archive/gtop/)
1. **thief: Temporal HIErarchical Forecasting** by Rob J Hyndman, Nikolaos Kourentzes (2018). [[R cran]](https://CRAN.R-project.org/package=thief) [[docu]](http://pkg.robjhyndman.com/thief/) [[github]](https://github.com/robjhyndman/thief)
1. **hts: Hierarchical and Grouped Time Series** by Rob J Hyndman, Alan Lee, Earo Wang, Shanika Wickramasuriya (2021). [[R cran]](https://CRAN.R-project.org/package=hts) [[docu]](https://pkg.earo.me/hts/) [[github]](https://github.com/earowang/hts)
1. **ProbReco: Score Optimal Probabilistic Forecast Reconciliation** by Anastasios Panagiotelis (2020). [[R archive]](https://cran.r-project.org/src/contrib/Archive/ProbReco/) [[github]](https://github.com/anastasiospanagiotelis/ProbReco)
1. **FoReco: Forecast Reconciliation** by Daniele Girolimetto, Tommaso Di Fonzo (2023). [[R cran]](https://CRAN.R-project.org/package=FoReco) [[docu]](https://danigiro.github.io/FoReco) [[github]](https://github.com/daniGiro/FoReco)
1. **bayesRecon: Probabilistic Reconciliation via Conditioning** by Dario Azzimonti, Nicolò Rubattu, Lorenzo Zambon, Giorgio Corani (2023). [[R cran]](https://CRAN.R-project.org/package=bayesRecon) [[github]](https://github.com/IDSIA/bayesRecon)
1. **fabletools: Core Tools for Packages in the 'fable' Framework** by Mitchell O'Hara-Wild, Rob J Hyndman, Earo Wang (2023). [[R cran]](https://CRAN.R-project.org/package=fabletools) [[docu]](https://fabletools.tidyverts.org/) [[github]](https://github.com/tidyverts/fabletools)

### Python
1. **pyhts: A python package for hierarchical forecasting** by Bohan Zhang, Yanfei Kang, Feng Li (2022). [[docu]](https://angelpone.github.io/pyhts/) [[github]](https://github.com/AngelPone/pyhts)
1. **GluonTS: Probabilistic Time Series Modeling in Python** by A. Alexandrov, K. Benidis, M. Bohlke-Schneider, V. Flunkert, J. Gasthaus, T. Januschowski, D. C. Maddix, S. Rangapuram, D. Salinas, J. Schulz, L. Stella, A. C. Türkmen, Y. Wang (2023). [[url]](https://ts.gluon.ai/)
    - Accompanying paper: **GluonTS: Probabilistic and Neural Time Series Modeling in Python** by Alexander Alexandrov, Konstantinos Benidis, Michael Bohlke-Schneider, Valentin Flunkert, Jan Gasthaus, Tim Januschowski, Danielle C. Maddix, Syama Rangapuram, David Salinas, Jasper Schulz, Lorenzo Stella, Ali Caner Türkmen, Yuyang Wang, _Journal of Machine Learning Research_ (2020). [[url]](http://jmlr.org/papers/v21/19-820.html)
1. **HierarchicalForecast: Probabilistic hierarchical forecasting with statistical and econometric methods** by Kin G. Olivares, Federico Garza, David Luo, Cristian Challú, Max Mergenthaler, Souhaib Ben Taieb, Shanika L. Wickramasuriya, Artur Dubrawski (2022). [[url]](https://nixtla.github.io/hierarchicalforecast)
    - Accompanying paper: **HierarchicalForecast: A Reference Framework for Hierarchical Forecasting in Python** by Kin G. Olivares, Federico Garza, David Luo, Cristian Challú, Max Mergenthaler, Souhaib Ben Taieb, Shanika L. Wickramasuriya, Artur Dubrawski (2023). [[arXiv]](https://arxiv.org/abs/2207.03517)


## Beyond forecasting and reconciliation <a name="beyond"/>
1. **The precision of national income estimates** by Richard Stone, D. G. Champernowne, J. E. Meade, _Review of Economic Studies_ (1942). [[doi]](https://doi.org/10.2307/2967664)
1. **Is aggregation necessarily bad?** by Yehuda Grunfeld, Zvi Griliches, _The Review of Economics and Statistics_ (1960). 
1. **Input-output and national accounts** by Richard Stone (1961).
1. **Should aggregation prior to estimation be the rule?** by John B. Edwards, Guy H. Orcutt, _The Review of Economics and Statistics_ (1969). 
1. **Best linear unbiased interpolation, distribution, and extrapolation of time series by related series** by Gregory C Chow, An-loh Lin, _The  of Economics and Statistics_ (1971). 
1. **Asymptotic behaviour of temporal aggregates of time series** by G C Tiao, _Biometrika_ (1972). [[doi]](https://doi.org/10.1093/biomet/59.3.525)
1. **Some consequences of temporal aggregation and systematic sampling for ARMAand ARMAX models** by K.R.W. Brewer, _Journal of Econometrics_ (1973). [[doi]](https://doi.org/10.1016/0304-4076(73)90015-8)
1. **Aggregate versus subaggregate models in local area forecasting** by D. M. Dunn, W. H. Williams, T. L. Dechaine, _Journal of the American Statistical Association_ (1976). [[doi]](https://doi.org/10.1080/01621459.1976.10481478)
1. **The estimation of large social account matrices** by R P Byron, _Journal of the Royal Statistical Society, Series A_ (1978). [[doi]](https://doi.org/10.2307/2344807) [[url]](http://www.jstor.org/stable/2344807)
1. **Corrigenda: The estimation of large social account matrices** by R P Byron, _Journal of the Royal Statistical Society. Series A_ (1979). [[doi]](https://doi.org/10.2307/2982515)
1. **Aggregation and proration in forecasting** by E Shlifer, R W Wolff, _Management Science_ (1979). [[url]](http://www.jstor.org/stable/2630330)
1. **Prior information and ARIMA forecasting** by Pierre A Cholette, _Journal of Forecasting_ (1982). 
1. **A note on the estimation of disaggregate time series when the aggregate is known** by Nicola Rossi, _The Review of Economics and Statistics_ (1982). 
1. **Forecasting temporally aggregated vector ARMA processes** by Helmut L\utkepohl, _Journal of Forecasting_ (1986). [[url]](http://onlinelibrary.wiley.com/doi/10.1002/for.3980050202/abstract)
1. **Modelling and forecasting linear combinations of time series** by Francisco A Pino, Pedro A Morettin, Ra\'ul P Mentz, _International Statistical Review/Revue Internationale de Statistique_ (1987). 
1. **Disaggregation methods to expedite product line forecasting** by C W Gross, J E Sohl, _Journal of Forecasting_ (1990). [[doi]](https://doi.org/10.1002/for.3980090304)
1. **The estimation of $M$ disaggregate time series when contemporaneous and temporal aggregates are known** by Tommaso Di Fonzo, _The Review of Economics and Statistics_ (1990). [[doi]](https://doi.org/10.2307/2109758)
1. **Constrained Forecasting: Some Implementation Guidelines** by Eugene B Fliedner, Vincent A Mabert, _Decision Sciences_ (1992). 
1. **Estimation of data measured with error and subject to linear restrictions** by Martin Weale, _Journal of Applied Econometrics_ (1992). 
1. **The effect of overlapping aggregation on time series models: an application to the unemployment rate in Brazil** by Luiz K Hotta, Pedro A Morettin, Pedro L Valls Pereira, _Brazilian Review of Econometrics_ (1992). 
1. **The effect of aggregation on prediction in autoregressive integrated moving-average models** by L. K. Hotta, J. Cardoso Neto, _Journal of Time Series Analysis_ (1993). 
1. **Constrained forecasting in autoregressive time series models: A Bayesian analysis** by Enrique De Alba, _International Journal of Forecasting_ (1993). 
1. **Restricted forecasts using exponential smoothing techniques** by A Lorena Rosas, Vi\'ctor M Guerrero, _International Journal of Forecasting_ (1994). 
1. **Highest-density forecast regions for nonlinear and non-normal time series models** by Rob J Hyndman, _J Forecasting_ (1995).
1. **Temporal aggregation and economic times series** by R.J. Rossana, J.J. Seater, _Journal of Business \& Economic Statistics_ (1995). [[doi]](https://doi.org/10.2307/1392389)
1. **Measurement error with accounting constraints: Point and interval estimation for latent data with an application to UK Gross Domestic Product** by Richard J Smith, Martin R Weale, Steven E Satchell, _The Review of Economic Studies_ (1998).
1. **A note on aggregation, disaggregation and forecasting performance** by Arnold Zellner, Justin Tobias, _Journal of Forecasting_ (2000). [[doi]](https://doi.org/10.1002/1099-131X(200009)19:5%3C457::AID-FOR761%3E3.0.CO;2-6)
1. **Data Processing and Reconciliation for Chemical Process Operations** by Jos\'e A Romagnoli, Mabel Cristina Sanchez (2000).
1. **Kalman filtering with state equality constraints** by Dan Simon, Tien Li Chia, _IEEE transactions on Aerospace and Electronic Systems_ (2002). 
1. **Forecasting euro area inflation: Does aggregating forecasts by HICP component improve forecast accuracy?** by K Hubrich, _International Journal of Forecasting_ (2005). 
1. **Optimal state estimation: Kalman, $H_\infty$, and nonlinear approaches** by Dan Simon (2006). 
1. **Benchmarking, Temporal Distribution, and Reconciliation Methods for Time Series** by Estela Bee Dagum, Pierre A Cholette (2006). [[doi]](https://doi.org/10.1007/0-387-35439-5)
1. **Temporal aggregation of univariate and multivariate time series models: A survey** by Andrea Silvestrini, David Veredas, _Journal of Economic Surveys_ (2008). [[doi]](https://doi.org/10.1111/j.1467-6419.2007.00538.x)
1. **Kalman filtering with state constraints: a survey of linear and nonlinear algorithms** by Dan Simon, _IET Control Theory \& Applications_ (2010).
1. **Simultaneous and two-step reconciliation of systems of time series: methodological and practical issues** by Tommaso Di Fonzo, Marco Marini, _Journal of the Royal Statistical Society, Series C_ (2011). [[doi]](https://doi.org/10.1111/j.1467-9876.2010.00733.x)
1. **Improving the performance of popular supply chain forecasting techniques** by Georgios P Spithourakis, Fotios Petropoulos, M Zied Babai, Konstantinos Nikolopoulos, Vassilios Assimakopoulos, _Supply Chain Forum: An International Journal_ (2011). 
1. **An aggregate--disaggregate intermittent demand approach (ADIDA) to forecasting: an empirical proposition and analysis** by Konstantinos Nikolopoulos, Aris A Syntetos, John E Boylan, Fotios Petropoulos, Vassilis Assimakopoulos, _Journal of the Operational Research Society_ (2011).
1. **Restoring accounting constraints in time series: methods and software for a statistical agency** by Benoit Quenneville, Susie Fortier, _Economic Time Series: Modeling and Seasonality_ (2012).
1. **Benchmarking large accounting frameworks: a generalized multivariate model** by Reinier Bikker, Jacco Daalmans, Nino Mushkudiani, _Economic Systems Research_ (2013).
1. **Demand forecasting by temporal aggregation** by Bahman Rostami-Tabar, M Zied Babai, Aris Syntetos, Yves Ducq, _Naval Research Logistics_ (2013). 
1. **Improving forecasting by estimating time series structural components across multiple frequencies** by Nikolaos Kourentzes, Fotios Petropoulos, Juan R Trapero, _International Journal of Forecasting_ (2014). 
1. **A systemic view of the ADIDA framework** by Georgios P Spithourakis, Fotios Petropoulos, Konstantinos Nikolopoulos, Vassilios Assimakopoulos, _IMA Journal of Management Mathematics_ (2014).
1. **A note on the forecast performance of temporal aggregation** by Bahman Rostami-Tabar, Mohamed Zied Babai, Aris Syntetos, Yves Ducq, _Naval Research Logistics_ (2014). 
1. **Forecasting with multivariate temporal aggregation: The case of promotional modelling** by Nikolaos Kourentzes, Fotios Petropoulos, _International Journal of Production Economics_ (2016). [[DOI]](https://doi.org/10.1016/j.ijpe.2015.09.011)  
1. **On the performance of overlapping and non-overlapping temporal demand aggregation approaches** by John E Boylan, M Zied Babai, _International Journal of Production Economics_ (2016).
1. **Integrated hierarchical forecasting** by Clint L.P. Pennings, Jan van Dalen, _European Journal of Operational Research_ (2017). [[doi]](https://doi.org/10.1016/j.ejor.2017.04.047)
1. **Demand forecasting by temporal aggregation: Using optimal or multiple aggregation levels?** by Nikolaos Kourentzes, Bahman Rostami-Tabar, Devon K Barrow, _Journal of Business Research_ (2017). [[DOI]](https://doi.org/10.1016/j.jbusres.2017.04.016)
1. **The impact of temporal aggregation on supply chains with ARMA (1, 1) demand processes** by Bahman Rostami-Tabar, M Zied Babai, Mohammad Ali, John E Boylan, _European Journal of Operational Research_ (2019).
1. **Assessment of aggregation strategies for machine-learning based short-term load forecasting** by Cong Feng, Jie Zhang, _Electric Power Systems Research_ (2020). [[doi]](https://doi.org/10.1016/j.epsr.2020.106304)
1. **Optimal Reconciliation of Seasonally Adjusted Disaggregates Taking Into Account the Difference Between Direct and Indirect Adjustment of the Aggregate** by Francisco Corona, Victor M Guerrero, Jesús López-Peréz , _Journal of Official Statistics_ (2021).
1. **Counterfactual Reconciliation: Incorporating Aggregation Constraints for More Accurate Causal Effect Estimates.** by Cengiz, Doruk, and Hasan Tekgüç, _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2022.08.011)
1. **Applicability of the M5 to forecasting at Walmart** by Brian Seaman, John Bowman, _International Journal of Forecasting_ (2022). [[doi]](https://doi.org/10.1016/j.ijforecast.2021.06.002)


## PhD and master thesis <a name="Thesis"/>
1. **Forecasting hierarchical time series** by Roman A Ahmed, _Monash PhD Thesis_ (2009). [[ur]](https://bridges.monash.edu/articles/thesis/Forecasting_hierarchical_time_series/14956233)
1. **Optimal forecasts for hierarchical and grouped time series** by Shanika L Wickramasuriya, _Monash PhD Thesis_ (2017). [[url]](https://bridges.monash.edu/articles/thesis/Optimal_forecasts_for_hierarchical_and_grouped_time_series/5032136?file=8500313)
1. **Essays in hierarchical time series forecasting and forecast combination** by Christoph Weiss, _University of Cambridge PhD Thesis_ (2018). [[doi]](https://doi.org/10.17863/CAM.21895)
1. **Probabilistic Forecast Reconciliation: Theory and Applications** by Puwasala Gamakumara, _Monash PhD Thesis_ (2020). [[url]](https://bridges.monash.edu/articles/thesis/Probabilistic_Forecast_Reconciliation_Theory_and_Applications/11869533?file=21758751)
1. **Forecast reconciliation: Methodological issues and applications** by Daniele Girolimetto, _UniPD PhD Thesis_ (2020). [[url]](https://www.research.unipd.it/handle/11577/3513823)

