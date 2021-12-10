FROM registry.cn-shanghai.aliyuncs.com/tcc-public/pytorch:1.4-cuda10.1-py3
ADD math.py /workspace
ADD run.sh /workspace
WORKDIR /workspace

CMD ["sh", "run.sh"]