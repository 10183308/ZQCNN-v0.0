ZQCNN-v0.0��ZuoQing����mini-caffeд��forward�⣬�������

# ������־

**2018-08-15�ո���**

(1)�����Ȼ�����ı���⣬ģ�ʹ�[TextBoxes](https://github.com/MhLiao/TextBoxes)ת�����ġ��Ҹ��˾����ٶ�̫��������׼ȷ�Ȳ��ߡ�

ע�������Ŀ���õ�PriorBoxLayer��SSD���PriorBoxLayer�ǲ�ͬ�ģ�Ϊ�˵���ZQCNN��ʽ��Ȩ�����޸���deploy.prototxt����Ϊdeploy_tmp.prototxt��
��[�˴�](https://pan.baidu.com/s/1XOREgRzyimx_AMC9bg8MgQ)����ģ�͡�

(2)���ͼƬ���ƣ�ģ�ʹ�[open_nsfw](https://github.com/yahoo/open_nsfw)ת�����ģ�׼ȷ�ȸ߲�����Ҳû�����

��[�˴�](https://pan.baidu.com/s/1asjZFr3iTliQ4xlNbtKUtw)����ģ�͡�

**2018-08-10�ո���**

�ɹ�ת��mxnet�ϵ�[GenderAge-r50ģ��](https://pan.baidu.com/s/1f8RyNuQd7hl2ItlV-ibBNQ) �Լ�[Arcface-LResNet100E-IR](https://pan.baidu.com/s/1wuRTf2YIsKt76TxFufsRNA)����תMobileFaceNetģ�Ͳ���һ����

����Model Zoo ����ת�õ�ģ�ͣ����Զ�ת������Ӧ���Կ졣

��ZQCNN.sln����SampleGenderAge�鿴Ч������E5-1650V4��CPU�����߳�ʱ�䲨���ܴ󣬾�ֵԼ1900-2000ms�����߳�400��ms��

**2018-08-09�ո���**

���mxnet2zqcnn���ɹ���mxnet�ϵ�MobileFaceNetת��ZQCNN��ʽ�����ܱ�֤����ģ��Ҳ��ת�ɹ���ZQCNN����֧�ֺܶ�Layer����

��һ���������mxnet2zqcnn.exe

�ڶ���������[model-y1.zip](https://pan.baidu.com/s/1If28BkHde4fiuweJrbicVA)Ȼ���ѹ

���������ڸղŽ�ѹ��Ŀ¼������������ mxnet2zqcnn.exe model-symbol.json model-0000.params test.zqparams test.nchwbin

���Ĳ����ü��±���test.zqparams, �ڵ�һ�У�Input Layer��������� C=3 H=112 W=112 Ȼ�󱣴�

���岽����test.zqparams��test.nchwbin���Ƶ�model�ļ����£�Ȼ����VS2015������SampleMobileNet.exe��ע�⹤��Ŀ¼��$(SolutionDir)

�Զ�ת�������ٶ����˲��٣������ֹ��޸�test.zqparams�����Բο�[ArcFace-MobileFaceNet-v0](https://pan.baidu.com/s/1f-Mfad-7zRvWcy3wYoPrUg)

**2018-08-07�ո���**

BUG�޸���֮ǰConvolution, DepthwiseConvolution, InnerProduct, BatchNormScale/ScaleĬ��with_bias=true�� ���ڸĳ�Ĭ��with_bias=false��Ҳ����֮ǰ�Ĵ����޷����ز���bias���⼸��Layer��

ʾ������������һ��Layer����ǰ��Ĭ��Ϊ��bias_term������Ĭ��û��bias_term

Convolution name=conv1 bottom=data top=conv1 num_output=10 kernel_size=3 stride=1 

**2018-08-06�ո���**

��������ʶ����LFW���ݿ�ľ��Ȳ��ԡ���ZQlibFaceID.sln���Կ������Project��

����C++����ļ��㾫����matlab���в�࣬ͳ�Ƴ��ľ���Ҳ��һЩ��𣬵��������0.1%���ڡ�

**2018-08-03�ո���**

֧�ֶ��̣߳�ͨ��openmp���٣���**��ע�⣬Ŀǰ���̷߳����ȵ��߳���**

**2018-07-26�ո���**

֧��MobileNet-SSD��caffemodelת���õ�ģ�Ͳο�export_mobilenet_SSD_caffemodel_to_nchw_binary.m����Ҫ�����matcaffe���С�
�������������汾[caffe-ZQ](https://github.com/zuoqing1988/caffe-ZQ)

**2018-06-05�ո���**

����ʱ������������Դ�롣
����˵��Ҫ����openblas������ֱ���õ�mini-caffe������Ǹ��汾���Լ���������ĺ�����



# Model Zoo

**�������**

[MTCNN](https://pan.baidu.com/s/1f6_wQ2kXiTZFyH6PFIDc2Q) ��[MTCNN](https://github.com/kpzhang93/MTCNN_face_detection_alignment)ת�ĸ�ʽ

**����ʶ��**

[SeetaFace](https://pan.baidu.com/s/17GySgiI8EASfOCuRizMAOw) LFWԼ97.8-97.9%��ÿ����ȡʱ��Լ110ms��3.6GHz

[SphereFace04bn256](https://pan.baidu.com/s/1YXt2PLbbUg9-VZITcMw5mQ) LFWԼ97.8%-97.9%�����߳�6-7ms���ٶ����

[SphereFace04](https://pan.baidu.com/s/1-Bb6yuU3eAN6U2ZdVsC5Mg) LFWԼ98.2%

[SphereFace04bn](https://pan.baidu.com/s/18uvL3p7PWRpJcHm00-7ABg) LFWԼ98.5%

[SphereFace06bn](https://pan.baidu.com/s/1LXjAoJWkWp-CT0sTgIHqfg) LFWԼ98.7%-98.8%

[SphereFace20](https://pan.baidu.com/s/1fGJU9PfPNBot6qGVeGlcug) LFWԼ99.2%-99.3%

[Mobile-SphereFace10bn512](https://pan.baidu.com/s/1BEP1pg5s3yJCLA2elqTB0A) LFWԼ98.6%-98.7%�����߳�15ms���Լ۱ȸ�

[ArcFace-r100](https://pan.baidu.com/s/1PeujQbIqFfgARIYAdRt3pw) LFWԼ99.80%-99.82%,���߳�1900���룬���߳�480���루�����ܴ�

[ArcFace-r50](https://pan.baidu.com/s/1qOIhCauwZNTOCIM9eojPrA) LFWԼ99.75%-99.78%,���߳�700�����

[ArcFace-r34](https://pan.baidu.com/s/1tRt6PxDg4UNv7yf9pMZ_LA) LFWԼ99.65%-99.70%,���߳�500��������

[ArcFace-MobileFaceNet-v0](https://pan.baidu.com/s/1f-Mfad-7zRvWcy3wYoPrUg) ��[model-y1.zip](https://pan.baidu.com/s/1If28BkHde4fiuweJrbicVA)ת�ĸ�ʽ��ת��֮����LFW��ֻ��99.13%-99.23%�����߳�33-35ms��4�߳�14-15ms

[ArcFace-MobileFaceNet-v1](https://pan.baidu.com/s/1b1g-hH7IWYxplY-XAvSz-Q) ���Լ���insightfaceѵ����һ�ѣ���matlab crop��C++ crop�� flip ��no-flip��Ҳ�������֣���LFW�ϵõ�׼ȷ��99.17-99.37%��

**����ʶ��**

[FacialEmotion](https://pan.baidu.com/s/1zJtRYv-kSGSCTgpvqc4Iug) ���������Fer2013ѵ��

**�Ա�����ʶ��**

[GenderAge-r50](https://pan.baidu.com/s/1FeuMLNG9jQ0CeD0ZANrY0g)��[insightface](https://github.com/deepinsight/insightface/wiki/Model-Zoo)��[gamodel-r50](https://pan.baidu.com/s/1f8RyNuQd7hl2ItlV-ibBNQ)ת�ĸ�ʽ��

**Ŀ����**

[MobileNetSSD](https://pan.baidu.com/s/1cyly_17cTOJBaCRiiQtWkQ) ��[MobileNet-SSD](https://github.com/chuanqi305/MobileNet-SSD)ת�ĸ�ʽ

[MobileNetSSD-Mouth](https://pan.baidu.com/s/1_l0Z1R34sOv2R73DB_zXyg) ����SampleDetectMouth

**���ּ��**

[TextBoxes](https://pan.baidu.com/s/1XOREgRzyimx_AMC9bg8MgQ) ��[TextBoxes](https://github.com/MhLiao/TextBoxes)ת�ĸ�ʽ

**ͼƬ����**

[NSFW](https://pan.baidu.com/s/1asjZFr3iTliQ4xlNbtKUtw) ��[open_nsfw](https://github.com/yahoo/open_nsfw)ת�ĸ�ʽ

# �������

(1)[�������������������洢������ʧ���٣�](https://zhuanlan.zhihu.com/p/35904005)

(2)[ǧ�������������������������ƶ����٣�](https://zhuanlan.zhihu.com/p/35955061)

(3)[����һ���mini-caffe�����Forward��](https://zhuanlan.zhihu.com/p/36410185)

(4)[��������ľ�������](https://zhuanlan.zhihu.com/p/36488847)

(5)[ZQCNN֧��Depthwise Convolution����mobilenet����һ��SphereFaceNet-10](https://zhuanlan.zhihu.com/p/36630082)

(6)[����ʱ������������һЩԴ��](https://zhuanlan.zhihu.com/p/37708639)

(7)[ZQCNN֧��SSD����mini-caffe����30%](https://zhuanlan.zhihu.com/p/40634934)

(8)[ZQCNN��SSD֧��ͬһ��ģ������ķֱ���](https://zhuanlan.zhihu.com/p/40676503)

(9)[ZQCNN��ʽ��99.78%���ȵ�����ʶ��ģ��](https://zhuanlan.zhihu.com/p/41197488)

(10)[ZQCNN��������ʶ����LFW���ݼ��ϵĲ��Դ���](https://zhuanlan.zhihu.com/p/41381883)

(11)[����mxnet�Ĵ��ȣ�����дmxnet2zqcnn](https://zhuanlan.zhihu.com/p/41667828)
