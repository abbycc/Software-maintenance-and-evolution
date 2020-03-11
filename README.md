# Software-maintenance-and-evolution
homework


### 选题: 软件特征对bug定位的影响分析
#### 目录
#### 背景

定位bug非常重要、困难且昂贵，对于大型系统尤其如此。为了解决这个问题，越来越多地使用自然语言信息检索技术来建议给定错误报告的潜在错误源文件。尽管这些技术具有很强的可伸缩性，但在实践中，它们的有效性在将错误精确定位到少量文件方面仍然很低。现在的定位方法大多通过分析软件的各种特征来进行bug定位，本报告将总结各种软件所用到的特征，并比较各个特征在定位bug中的影响。

#### 内容组成

* bug定位方法的综述
  * 总结主流的各种bug定位方法，以及他们如何提取软件特征用于定位的
* 软件特征总结
  * 对综述的内容进行概括，比较它们的异同
* 软件特征对bug定位所产生的影响
  * 根据bug定位的方法进行特征提取，然后采用不同的配置进行比较，通过比较来确定各个特征对于最后定位结果的影响。
#### 研究方法

* **BLUiR**

* **Amalgam**

* **Lobster**

* **BLIA**

  （包括但不限制于上述）

#### 软件特征
* 报告和源代码的相似
* 相似报告
* 代码结构
* 堆栈跟踪
* 版本历史
#### 参考文献

[1] Tantithamthavorn, Chakkrit, Abebe, et al. The impact of IR-based classifier configuration on the performance and the effort of method-level bug localization[J]. IST 2018:160-174.

[2] Wang SW, Lo D. Version history, similar report, and structure: putting them together for improved bug localization. ICPC 2014: 53-63.

[3] Zhang W, Li ZQ, Qing Wang, Juan Li. FineLocator: A novel approach to method-level fine-grained bug localization by query expansion. Information & Software Technology, 2019,110:121-135.

[4] Koyuncu A, Bissyande TF, Kim DS, Liu K, Klein J, Monperrus M, Traon YL. D&C: A divide-and-conquer approach to IR-based bug localization. IEEE Trans. on Software Engineering, 2019.

[5] Youm KC, Ahn J, Lee E. Improved bug localization based on code change histories and bug reports. Information & Software Technology, 2017,82:177-192. IST

[6]  Dilshener T, Wermelinger M, Yu YJ. Locating bugs without looking back. Automated Software Engineering, 2018,25(3):383-434.

[7] Rahman MM, Roy CK. Improving IR-based bug localization with context-aware query reformulation. In: Proc. of the 26th ACM SIGSOFT Int’l Symp. on Foundations of Software Engineering. ACM Press, 2018:621-632.

[8] Rath M, Lo D, Mäder P. Analyzing requirements and traceability information to improve bug localization. MSR 2018:442-453.

[9] Wang YJ, Y Yuan, Tong HH, Huo X, Li M, Xu F, Lu J. Bug localization via supervised topic modeling. ICDM 2018: 607-616.

[10] Loyola P, Gajananan K, Satoh F. Bug localization by learning to rank and represent bug inducing changes. CIKM 2018:657-665.



