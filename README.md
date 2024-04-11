제목: 협업 기반 소프트웨어 조사
팀원: 노어노문학과/2019115685/이호윤(12Leehoyun)
      사회학과/2022114338/권하늬(Floif)
      일어일문학과/2019115567/최원빈(CHOIWONBIN12)
      불어불문학과/2021114245/장지우(ZiwooJang)
      고고인류학과/2023028700/박성현(Sunghyeon04)
1. 개요
블렌더는 무료 오픈 소스 3D 그래픽 소프트웨어이다. 3D 모델링, 애니메이션, 시뮬레이션, 렌더링, 비디오 편집 등의 다양한 기능을 제공한다. 각각의 전문 프로그램들에 비해 기능은 조금씩 부족해 보일지라도 그 모든 분야의 기능들이 한 프로그램에 완전히 통합되어 있다는 점이 장점이다. 또한 사용자들은 다양한 플랫폼에서 블렌더를 활용할 수 있으며, 커뮤니티 기여와 업데이트를 통해 지속적으로 발전하고 있다.

2. 라이선스: GNU GPLv2 이상

3. 주요기능
1) 모델링(Modeling)
   블렌더는 다양한 모델링 도구를 제공하여 간단한 기하학적 모양부터 복잡한 유기적 구조물까지 사용자의 다양한 요구를 충족시킨다. 블렌더가 보유하고 있는 다양한 모델링 기능에 대해서 알아보자. 
   ① 다각형 모델링
     블렌더는 대부분의 3D 모델링 워크플로우의 기초인 다각형 모델링 분야에서 우수한 성과를 거두고 있다. 사용자는 정점, 모서리 및 면을 생성하고 조작하여 3D 객체를 구축할 수 있다. 블렌더는 정점, 모서리 및 면 선택을 포함한 다양한 선택 모드를 지원하여 모델링 프로세스를 정밀하게 제어할 수 있습니다.
   ② 조각
     블렌더에는 유기적 모양과 세부 정보를 직접 메쉬 표면에 조각하는 강력한 조각 도구가 포함되어 있다. 블렌더에서 조각하는 것은 가상의 클레이를 다루는 것과 유사하며 브러시를 사용하여 지오메트리를 추가하거나 제거하고 표면을 부드럽게 만들고 복잡한 세부 정보를 정제할 수 있다.
   ③ 모디파이어
     블렌더에는 객체에 적용하여 지오메트리를 파괴하지 않고 수정하는 다양한 모디파이어가 있다. 서브디비전 서페이스, 베벨, 미러 및 불리언과 같은 모디파이어를 사용하여 복잡한 모양과 효과를 수동으로 편집하지 않고 생성할 수 있다.
   ④ 절차적 모델링
     블렌더의 절차적 모델링 기능을 사용하면 알고리즘을 사용하여 복잡한 모양과 패턴을 생성할 수 있다. 모디파이어, 절차적 텍스처 및 지오메트리 노드 및 애니메이션 노드와 같은 노드 기반 시스템을 사용하면 매개 변수 및 동적 모델링 워크플로를 통해 복잡한 지오메트리를 절차적으로 생성할 수 있다.
   ⑤ 레토폴로지
     레토폴로지는 기존 메쉬 위에 새롭고 더 깨끗한 메쉬 토폴로지를 생성하는 프로세스로, 기하학적 또는 기계적 객체를 최적화하거나 게임용 에셋을 생성하는 데 사용된다. 
   ⑥ 정밀 모델링
     블렌더는 스냅 옵션, 그리드 스냅, 정점 스냅 및 변환에 정확한 숫자 값을 입력할 수 있는 기능 등 정밀 모델링을 위한 기능을 제공한다. 이러한 도구를 사용하면 건축, 기계 또는 기타 정밀 객체를 모델링할 때 정확성을 보장받을 수 있다.
   ⑦ 애드온 및 사용자 정의
     블렌더의 모델링 기능은 애드온 및 사용자 지정 스크립트를 통해 확장할 수 있다. 다양한 모델링 작업을 위한 전문 도구 및 워크플로를 제공하는 다양한 애드온 라이브러리가 있으며 블렌더의 파이썬 API를 사용하면 사용자는 특정 요구 사항에 맞게 개인화된 도구 및 워크플로를 개발할 수 있다.
   블렌더의 모델링 기능은 유기적인 형태부터 복잡한 기하학적 모양까지 다양한 3D 에셋을 생성하기 위한 포괄적인 도구 세트를 제공하여 유연성, 효율성 및 정확성을 제공한다. 블렌더는 모델링 측면에서 다양하고 유연한 도구를 제공하여 사용자는 고품질의 3D 모델을 만들 수 있다.

2) 리깅(Rigging)
![Rig1](https://github.com/12Leehoyun/oss_12/assets/166006462/dad69f60-bdad-4d86-a621-0da5024d2165)
   모델링 기능으로 3D 모델이 만들어졌다면 그 다음은 리깅이라는 기능을 통해 모델을 움직이도록 할 차례다. 리깅은 간단히 말하자면 3D모델의 뼈대를 만들고 이를 제어하도록 해주는 기능이다. 이를 통해 3D 모델이나 객체를 움직이고 애니메이션화 시킬 수 있다.

   ① 모델과 뼈대 연결
   리깅의 핵심은 모델과 뼈대를 연결하는 것이다. 뼈대는 모델이 움직이는데 사용되며, 블렌더에서는 이를 손쉽게 생성하고 조작할 수 있다. 이 과정에서 뼈대를 모델에 맞게 배치하고 각 뼈가 어떤 피부를 당길지 연결해 주는 작업을 한다. 

   ② 뼈대 제어 시스템 추가 
   뼈대를 효과적으로 제어하기 위해 제어 시스템을 추가할 수 있다. 이는 일반적으로 뼈대에 연결된 컨트롤러로 구성되며, 모델을 움직이고 애니메이션화하기 위해 사용된다. 블렌더는 다양한 제어 시스템을 제공하여 사용자가 원하는 스타일과 복잡도에 맞게 선택할 수 있습니다.

   ③ 좌우 대칭 기능
   각 뼈의 이름을 지을 때 좌우를 구분해주는 접미사를 붙일 수 있다. L과 R, -left와 -right 등 좌우를 구분하는 접미사라면 블렌더가 자동으로 편집 과정에서 각 뼈의 좌우 대칭을 유지시켜준다.
   
   ![Rig2](https://github.com/12Leehoyun/oss_12/assets/166006462/fb603679-c7bd-4c79-9c87-8dc3b86b8025)
   
   ④ Inverse Kinematics 
   목표 지점에 따라 자동으로 관절을 조정하여 모델을 움직이는 기능이다. 이 기능을 사용하면 캐릭터의 손이나 발을 목표 지점에 맞게 움직일 수 있다. 따라서 원하는 동작을 빠르고 쉽게 만들 수 있다.
   
   ![rig3](https://github.com/12Leehoyun/oss_12/assets/166006462/805fbfdf-340d-4ec1-bd66-89fdd0795a29)
   
   ⑤ 움직임 테스트
   리깅된 모델을 사용하여 움직임을 테스트하고 조정한다. 이 과정은 모델이 자연스럽게 움직이고 원하는 애니메이션을 구현할 수 있는지 확인하는 데 필요하다. 블렌더는 실시간 뷰포트 애니메이션 재생과 다양한 애니메이션 테스트 도구를 제공하여 효율적인 테스트를 가능하게 해준다.
   
   리깅은 3D 애니메이션 작업에서 중요한 단계이며, 블렌더는 리깅에 있어서 강력한 도구를 제공한다. 사용자는 블렌더의 다양한 리깅 기능을 활용하여 보다 생동감 있고 풍부한 애니메이션을 만들어낼 수 있다.

4) 스컬프팅(Sclupting)

  3D 모델의 형태를 조각하고 수정하는 작업을 위한 도구를 제공한다. 이를 통해 사용자는 자연스러운 형태와 디테일을 가진 3D 모델을 생성할 수 있다. 부드러운 입체 모형을 누르고, 변형시키고, 무늬를 내고, 끌어당기는 방식으로 형태를 만든다.
   동물이나 식물과 같은 생물, 돌이나 지형같은 자연물, 인간의 신체를 만드는 데에 많이 쓰인다. 스컬프팅의 기능에는 브러시 및 브러시 설정, 다이나믹 토플로지, 대규모 모델 처리, 레이어 및 마스크, 실시간 렌더링, 디테일 및 텍스처링 총 6가지가 있다.

   ![스컬프팅](https://github.com/12Leehoyun/oss_12/assets/166000743/b6f9126b-64e5-4144-b549-81677e59162a)


 ① 브러시와 브러시 설정
 
   블렌더의 스컬프팅 기능은 다양한 형태와 효과를 가진 브러시를 제공한다. 예를 들어, 조각 브러시, 블랜드 브러시, 폴리쉬 브러시 등이 있다. 각 브러시는 모델에 다른 종류의 효과를 적용한다.
   
   사용자는 브러시의 크기, 강도, 각도, 그리고 텍스처와 같은 속성을 조정하여 원하는 효과를 얻을 수 있다.
   
 ② 다이나믹 토폴로지
 
   Blender는 다이나믹 토폴로지라는 기능을 통해 모델의 표면을 자동으로 조절하여 디테일한 부분을 더 자연스럽게 만들어 준다. 이를 통해 사용자는 세부적인 수정 작업을 더욱 효율적으로 수행할 수 있다.

![토폴로지](https://github.com/12Leehoyun/oss_12/assets/166000743/4abe89f1-2cc2-4ef3-afa9-26e68a7fa1d5)


 ③ 대규모 모델 처리
 
   Blender의 스컬프팅 기능은 대규모 모델에도 효과적으로 적용할 수 있다 다양한 최적화 기능을 통해 대규모 모델을 효율적으로 처리할 수 있다.
   
 ④ 레이어 및 마스크
 
   Blender는 스컬프팅 작업을 위한 레이어 및 마스크 기능을 제공한다. 이를 통해 사용자는 작업을 조직화하고 특정 부분에만 작업을 적용할 수 있다.
   
 ⑤ 실시간 렌더링
 
   Blender는 실시간 렌더링 기능을 제공하여 사용자가 작업하는 동안 변경 사항을 실시간으로 확인할 수 있다. 이를 통해 작업의 효율성을 높일 수 있다.
   
 ⑥ 디테일 및 텍스처링
 
   디테일 기능을 사용하여 모델에 디테일한 부분을 추가할 수 있다. 또한, 텍스처링 작업을 통해 모델에 색상이나 질감을 추가할 수 있다.
   
이처럼 Blender의 스컬프팅 기능은 다양한 3D 모델링 작업에 유용하게 활용될 수 있으며, 사용자가 원하는 모델을 빠르고 효과적으로 만들 수 있도록 도와준다. 

7) 물리 시뮬레이션(Physics)

    애니메이션 속 일렁이는 강가의 물결, 바람에 흩날리는 벚꽃, 무너지는 건물과 폭발하는 자동차는 어떻게 구현되는 것일까? 바로 블렌더의 ‘물리 시뮬레이션(Physics)’ 기능이 이 모든 것을 가능하게 한다. 물리 시뮬레이션은 현실에서 일어날법한 다양한 물리 현상들을 사실적으로 프로젝트에 구현할 수 있게 하는 기능이다. 해당 기능은 다시 ‘강체, 연체, 천, 유체, 입자, 다이나믹 페인트, 힘, 충돌’까지 총 8가지의 세부 기능으로 분류할 수 있다.
      ![yosuke-inoue-rigidbody-cover](https://github.com/12Leehoyun/oss_12/assets/165813759/6a689d34-22b2-4402-a473-c96fcdadefc3)
      

   ① 강체(Rigid body)
 
   ‘강체’는 가구, 돌, 건물 등의 고체를 구현하는 시뮬레이션을 수행할 때 사용하는 기능이다. 크게 ‘패시브 시뮬레이션’과 ‘액티브 시뮬레이션’으로 나뉘며 이를 통해 고체의 정적인 움직임뿐만 아니라, 동적인 움직임 또한 구현할 수 있다.
  
   ② 연체(Soft body)
 
   ‘연체’는 변형이 가능한 물체의 시뮬레이션에 이용되는 기능으로, 캐릭터의 신체 움직임, 고무의 탄력성, 바람에 흔들리는 나뭇가지 등을 구현할 때 사용하는 기능이다.
  
   ③ 천(Cloth)
 
   ‘천’은 옷감, 깃발 등을 프로젝트 내에서 구현하고자 할 때 사용되는 기능이다. 해당 기능을 통해 제작자는 움직이는 물체, 공기 역학 등에 영향을 받는 물체의 다양한 모습을 사실적으로 표현할 수 있다.
  
   ④ 유체(Fluid)
 ![physics_fluid_introduction_liquid-example](https://github.com/12Leehoyun/oss_12/assets/165813759/c752d77a-2bc1-4870-b15c-e07a9cf979a3)
   ‘유체’는 액체와 같은 물리적 특성을 이용한 시뮬레이션을 구현할 때 사용한다. 예로 물체가 물속에 떨어는 상황을 구현할 때, 해당 기능을 통해 떨어지는 물체로 인해 출렁이는 물결과 물속 안의 물체의 진행과정 등을 시각적으로 표현할 수 있다.
  
   ⑤ 입자(Particle System)
 
   ‘입자’는 눈에 보이지 않는 아주 미세한 입자에 물리적인 환경을 부여하여, 더욱더 현실적인 시각적 효과를 구현하기 위해 사용하는 기능이다. 해당 기능을 사용하면 불꽃, 연기, 구름, 머리카락 등이 바람과 중력에 의해 움직이는 모습을 세밀하게 시뮬레이션해 볼 수 있다.
  
   ⑥ 다이내믹 페인트(Dynamic Paint)
 
   ‘다이내믹 페인트’는 환경의 다양한 역학적 조건에 따라 달라지는 표현 대상의 색상, 질감 등을 구현해 내는 기능이다. 이는 눈 위의 발자국, 땅을 점차 젖게 하는 빗방울, 벽에 칠해진 페인트 등 다양한 효과를 가능하게 한다.
  
   ⑦ 힘 (Forces)
 
   ‘힘’은 프로젝트 공간 속에서 오브젝트에 영향을 주는 물리적 힘을 재현하는 기능이다. 해당 기능으로 표현할 수 있는 힘에는 대표적으로 중력, 풍력, 동력, 전기력 등이 있다.
  
   ⑧ 충돌 (Collision)
 
   ‘충돌’은 앞서 말한 입자, 천, 유체 등의 기능을 사용할 때 다루는 소프트 계열의 물체 충돌을 재현할 때 사용되는 기능이다. 

   이렇게 블렌더의 물리 시뮬레이션 기능은 다양한 세부 기능을 바탕으로 프로젝트의 현실적인 시각적 효과를 표현할 수 있게 한다. 이는 소프트웨어 사용자로 하여금 창의적인 아이디어를 실험해 볼 수 있는 장을 만들어 애니메이션 및 영화제작, 게임 개발, 제품 디자인, 과학 연구 등 다양한 산업 분야에서 널리 사용되고 있다. 

8) UV 편집(UV Editing/Mapping)

   블렌더의 UV 편집 기능은 3D 모델의 텍스쳐 매핑 및 UV 매핑을 위한 강력한 도구를 제공한다. 모델의 표면에 텍스쳐를 적용하기 위해 필요한 UV 맵을 조작,편집하는 과정인데, 이를 통해 모델의 각 부분에 올바르게 텍스쳐를 배치하고, 디테일을 추가하거나 수정할 수 있다.
 
 
   ① UV Editor 
   ![editors_uv_introduction_texturing-header](https://github.com/12Leehoyun/oss_12/assets/166011915/3061598d-9a98-4213-9b0d-cbc974f84749)
   UV 편집기는 텍스쳐 매핑을 위한 인터페이스를 제공한다. 여기에서 UV 맵을 조작하고, 텍스쳐를 레이아웃하고, 편집할 수 있다.

   ② UV Unwrapping

    ![blender-uv-unwrap](https://github.com/12Leehoyun/oss_12/assets/166011915/c5017924-0845-41bd-a75d-d3949af035e5)

   모델의 표면을 펼쳐 UV 맵을 생성하는 과정이다. 블렌더는 다양한 언랩핑 알고리즘을 제공하여 사용자가 모델의 형태와 텍스쳐 배치에 따라 적합한 방법을 선택할 수 있다.

    ③ UV Mapping Tools
    ![stIh4](https://github.com/12Leehoyun/oss_12/assets/166011915/4c9b79f8-6fe8-48e1-a14d-805881b1c037)
    다양한 매핑 도구를 통하여 UV맵을 조작하고 편집할 수 있게 한다. 이 도구들은 UV맵의 위치, 크기, 회전 등을 조정하는 데 사용된다.

    ④ UV Texture Painting

   ![sculpt-paint_painting_texture-paint_introduction_example](https://github.com/12Leehoyun/oss_12/assets/166011915/9f7b9224-8f0f-4d3d-b2f8-68a9328d5738)

   직접 텍스쳐를 그리거나 편집할 수 있는 텍스쳐 페인팅 도구이다. 이를 통해 텍스쳐의 디테일을 추가하거나 수정할 수 있다.

    ⑤ UV Sync Selection

    모델의 3D View와 UV 편집기를 동기화하여 선택한 부분끼리 서로 연결되도록 한다. 이를 통해 UV 맵에서 선택한 부분에 대응하는 모델의 부분을 식별하고 편집할 수 있다.
    
    이러한 기능들은 3D 모델의 텍스쳐를 효과적으로 만들고 수정하는 데 도움을 준다. UV 편집 기능으로 인하여 제작자들이 모델에 높은 품질의 텍스쳐를 적용하여 현실감 있고 매력적인 작품을 만들 수 있게 된다.
