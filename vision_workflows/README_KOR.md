# NVIDIA NIM을 활용한 비전 워크플로

이 서브모듈에는 비전 애플리케이션을 위한 NIM 기반 워크플로가 포함되어 있습니다. 이 서브모듈에 접근하려면 다음 방법 중 하나를 사용하십시오.

1) nvidia/GenerativeAIExamples 저장소를 재귀적으로 클론합니다.
```
git clone https://github.com/nvidia/GenerativeAIExamples --recurse-submodules
```

2) 이미 ```--recurse-submodules``` 플래그 없이 저장소를 클론했다면 수동으로 서브모듈을 가져올 수 있습니다.
```
git submodule update --init
```

3) 비전 워크플로 저장소를 직접 클론할 수도 있습니다.
```
git clone https://github.com/NVIDIA/metropolis-nim-workflows.git
```

서브모듈을 가져오거나 저장소를 직접 클론한 뒤에는 제공되는 비전 NIM 워크플로를 살펴볼 수 있습니다.

## 사용 가능한 워크플로

### [VLM 경보 시스템](https://github.com/NVIDIA/metropolis-nim-workflows/blob/main/nim_workflows/vlm_alerts/README.md)
<p float="left">
<img src="readme_assets/vlm_alert.gif" alt="" width="800"/>
</p>

### [구조화된 텍스트 추출](https://github.com/NVIDIA/metropolis-nim-workflows/tree/main/nim_workflows/vision_text_extraction)
<p float="left">
<img src="readme_assets/text_extraction.gif" alt="" width="800"/>
</p>

### [NVCLIP 멀티모달 검색](https://github.com/NVIDIA/metropolis-nim-workflows/tree/main/nim_workflows/nvclip_multimodal_search)
<p float="left">
<img src="readme_assets/nvclip_multimodal.gif" alt="" width="800"/>
</p>

### [NV-DINOv2 퓨샷 분류](https://github.com/NVIDIA/metropolis-nim-workflows/tree/main/nim_workflows/nvdinov2_few_shot)
<p float="left">
<img src="readme_assets/few_shot.gif" alt="" width="800"/>
</p>

자세한 내용은 [이 페이지](https://github.com/NVIDIA/metropolis-nim-workflows)를 참고하세요.
