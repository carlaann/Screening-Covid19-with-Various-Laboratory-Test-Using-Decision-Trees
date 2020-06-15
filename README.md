
#### Project name: Screening Covid19 with Various Laboratory Test
# Description: COVID-19 is a newly discovered infectious disease that can cause mild to severe respiratory illness.  It appears those with underlying conditions such as diabetes, hypertension, cardiovascular disease, and other serious illness are more at risk.  COVID-19 is an RNA virus which belongs to the family coronavirus.  It was initially emerged in China around December 2019.  The wide spread of this virus has become a pandemic. During this pandemic testing, there has been issues from faulty test kits, lack of supplies, inadequate testing facilities, etc. There are delays from testing that provides the definitive diagnosis.  This could take from 3 to 7 days. My goal is to explore other laboratory test that can provide a rapid answer for the patients until the PCR test results are available.
#1.	Table of Contents: 
EDA
# a. Dropping junk variables
# b.	Correlation matrix
# c.	Handling missing values and remaining variables:
# d.	Train and Validation split:
#   •	Plotting Decision Tree
# e.	Feature Importance
#   •	Plotting decision tree with only top feature
#   •	Confusion matrices and training validations
# f.	Bivariate Analysis of top features
#2.	Installation: 
#   a.	To execute this project, the following applications are required:
#       •	Python3 or Anaconda distribution with Python 3
#       •	Jupyter or any other notebook
#       •	Anaconda distribution alone should be enough. Find it https://www.anaconda.com/products/individual
# 3. Usage: 
#    Updates for this project will monitored.  The data has been retrieved from  https://www.kaggle.com/einsteindata4u/covid19?              select=dataset.xlsx#
# 4.	Contributing
#     a.	Credits: 
#     Carla Harrell
# Acknowledgements:
# Y. Huang, M. Tu, S. Wang, S. Wang, S. Chen, W. Zhou, et al.Clinical characteristics of laboratory confirmed positive cases of SARS-CoV-2 infection in Wuhan, China: a retrospective single center analysis. Travel Med Infect. Dis. (2020), p. 101606, 10.1016/j.tmaid.2020.101606
# Chaolin Huang*, Yeming Wang*, Xingwang Li*, Lili Ren*, Jianping Zhao*, Yi Hu*, Li Zhang, Guohui Fan, Jiuyang Xu, Xiaoying Gu, Zhenshun Cheng, Ting Yu, Jiaan Xia, Yuan Wei, Wenjuan Wu, Xuelei Xie, Wen Yin, Hui Li, Min Liu, Yan Xiao, Hong Gao, Li Guo, Jungang Xie, Guangfa Wang, Rongmeng Jiang, Zhancheng Gao, Qi Jin, Jianwei.  Wang, Bin Cao (2020). Clinical features of patients infected with 2019 novel coronavirus in Wuhan, China. https://www.thelancet.com/pdfs/journals/lancet/PIIS0140-6736(20)30183-5.pdf
# Y. Cheng, R. Luo, K. Wang, R. Luo, K. Wang, M. Zhang, et al(2020).Clinical characteristics of 140 patients infected with SARS‐CoV‐2 in Wuhan, China.
#.Huang, C.; Wang, Y.; Li, X.; Ren, L.; Zhao, J.; Hu, Y.; Zhang, L.; Fan, G.; Xu, J.; Gu, X.; Cheng, Z.; Yu, T.; Xia, J.; Wei, Y.; Wu, W.; Xie, X.; Yin, W.; Li, H.; Liu, M.; Xiao, Y.; Gao, H.; Guo, L.; Xie, J.; Wang, G.; Jiang, R.; Gao, Z.; Jin, Q.; Wang, J.; Cao, B., Clinical features of patients infected with 2019 novel coronavirus in Wuhan, China. Lancet 2020, doi: 10.1016/S0140-6736(20)30183-5.
# Chen, N.; Zhou, M.; Dong, X.; Qu, J.; Gong, F.; Han, Y.; Qiu, Y.; Wang, J.; Liu, Y.; Wei, Y.; Xia, J.; Yu, T.; Zhang, X.; Zhang, L.(2020). Epidemiological and clinical characteristics of 99 cases of 2019 novel coronavirus pneumonia in Wuhan, China, a descriptive study. Lancet 2020, doi:10.1016/s0140-6736(20)30211-7 
# Betjes, M. G., Immune cell dysfunction and inflammation in end-stage renal disease. Nat Rev Nephrol, 2013, 9 (5), 255-65. 
# Ishigami, J.; Grams, M. E.; Chang, A. R.; Carrero, J. J.; Coresh, J.; Matsushita, K., CKD and Risk for Hospitalization With Infection: The Atherosclerosis Risk in Communities (ARIC) Study. Am J Kidney Dis 2017, 69 (6), 752-761.
# Cohen-Hagai, K.; Rozenberg, I.; Korzets, Z.; Zitman-Gal, T.; Einbinder, Y.; Benchetrit, S., Upper Respiratory Tract Infection among Dialysis Patients. Isr Med Assoc J 2016, 18 (9), 557-560. 
# Sibbel, S.; Sato, R.; Hunt, A.; Turenne, W.; Brunelli, S. M., The clinical and economic burden of pneumonia in patients enrolled in Medicare receiving dialysis: a retrospective, observational cohort study. BMC nephrol 2016, 17 (1), 199. 
# Vanmassenhove, J.; Kielstein, J.; Jorres, A.; Biesen, W. V., Management of patients at risk of acute kidney injury. Lancet 2017, 389 (10084), 2139-2151. 
# Wang, D.; Hu, B.; Hu, C.; Zhu, F.; Liu, X.; Zhang, J.; Wang, B.; Xiang, H.; Cheng, Z.; Xiong, Y.; Zhao, Y.; Li, Y.; Wang, X.; Peng, Z., Clinical Characteristics of 138 Hospitalized Patients With 2019 Novel Coronavirus-Infected Pneumonia in Wuhan, China. JAMA 2020, doi:10.1001/jama.2020.1585
•	License: Not Applicable.
