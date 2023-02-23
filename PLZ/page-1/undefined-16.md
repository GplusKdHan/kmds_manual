# 배치 양식 파일의 구조 및 작성 요령

### 배치 양식 파일의 구조 및 작성 요령

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2F8IKuaXnEyISqteb3eGIV%2Fimage.png?alt=media\&token=de0a1db2-96f1-4384-9e5d-9a4675f51c33)

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FfvFHqgqGqz6G5qRscVMs%2Fimage.png?alt=media\&token=d27c657d-1f0d-4a77-b8ea-9dc3c543430d)

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2F3pDuV8aaC8NmZGekX1qF%2Fimage.png?alt=media\&token=57f645b0-5eb8-49fa-8dd8-69b43c64054f)

배치 파일의 열은 입력 데이터의 항목들을 나타내고, 각 항목의 이름(①-⑦)이 배치 파일의 헤더(열 제목)로 구성된다.

배치 파일의 행(ⓐ-ⓒ)은 데이터셋을 구성하는 여러 데이터 중 하나의 입력 데이터를 나타낸다. 입력 UI를 통해 입력한 하나의 데이터를 입력했다면, 이는 하나의 행으로 표현된다.

배치 파일의 헤더는 그 값 자체만으로 표준 소재 시스템의 구조에서 어느 곳에 위치하는지 알 수 있도록 하였다.

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FfThyz9fzRu7HJ8Mw8LFr%2Fimage.png?alt=media\&token=86aec496-b0c7-4eb0-81f4-38391e9cb3e1)

1.  1\.

    마침표(.) 앞쪽은 그룹 혹은 폴더를 나타낸다.
2.  2\.

    대괄호(\[숫자])는 동일한 값이 여러 번 반복되는 배열을 표현한다.
3.  3\.

    가장 오른쪽에 위치한 값이 입력할 항목을 나타낸다.

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2F4Pmo1BsZkIUM5HS5P9pW%2Fimage.png?alt=media\&token=dd899da5-0e51-4ff9-83ce-1c30e8a041e9)

Metadata.Contributor\[1].Name의 의미는 Metadata 그룹의 2번째 (0이 첫번째 이므로 1이 두번째가 됨) Contributor의 Name을 뜻한다.

#### 3. 배치 파일을 이용하여 Composition 입력하기 <a href="#3.-composition" id="3.-composition"></a>

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FDFbOlL5gfS4q03rrc8ec%2Fimage.png?alt=media\&token=eba0e94d-7e32-4610-a409-ba81ffb99875)

Parameter Type - Periodic

**1) element 항목을 선택할 때 - Parameter Type : Periodic Table인 항목**

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FKrg6K8HYlVf47DWbbfVK%2Fimage.png?alt=media\&token=008731a7-6d80-4668-bf57-7468349ce86c)

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FGM5ohLnQBg3GE22ILChj%2Fimage.png?alt=media\&token=3b8c037f-df3a-4a5f-bf9a-aca3d74127fa)

주기율표에서 원소 다수 선택 후 확인 버튼 눌렀을 때 확인할 수 있는 화면

Parameter Type이 Periodic Table인 항목들 중 Unit(단위), Uncertainty(불확실성)은 단일로 표출되며, Element 같은 경우, 다중 선택이 가능하며 다중 선택 된 원소들로 사용자 지정 항목에 표출된다.

Uncertainty 입력 시, 뒤 원소들에게 부가적으로 값이 추가된다.

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2Fe0wkGfKUtjpUKgOb6VwC%2Fimage.png?alt=media\&token=35d8eaea-a709-4870-93fe-e1e706583b2d)

Parameter Type - Periodic Table 작성 예시

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2F2PU0SkSaTWVLRSW505Ss%2Fimage.png?alt=media\&token=ae3b9564-0baa-4361-b494-cf45fbb421e0)

배치 기반 데이터 등록 시 파일을 등록해야 하는 경우에는 등록할 파일명을 추가한 후 배치 파일을 업로드할 때 함께 업로드 해야 한다.

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FSYao8Nbcv0BmLF2YQBIS%2Fimage.png?alt=media\&token=3305dafc-924c-4285-9d5c-1999bbfa9801)

#### 5. 배치 파일을 이용하여 Analysis Method/Process 링크하기 <a href="#5.-analysis-method-process" id="5.-analysis-method-process"></a>

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2F1h6J1o6Ycrq6eblBCiJL%2Fimage.png?alt=media\&token=eced8dff-2bbf-460c-8f26-1e00860e9149)

Measurement에 해당하는 값은 analysis method에서 생성한 테스트 방법에 대한 링크이다.

배치 파일에서 이를 표현하기 위해서는 생성한 analysis method를 정확하게 입력해야 한다.

#### 6. 배치 파일을 이용하여 String 등록하기 <a href="#6.-string" id="6.-string"></a>

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FViqp8rk8hXjnQkTdqu5G%2Fimage.png?alt=media\&token=8b1cc0d6-6f5c-4fa2-ae3c-974ea7d9113f)

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FKzi8EVrM76bxIdBwQC1a%2Fimage.png?alt=media\&token=e9bbd6ab-bc2d-460e-858e-796f8d835d19)

Parameter Type - String 작성 예시

위 화면과 같이 String(문자열) 형식으로 입력해야 한다.

#### 7. 배치 파일을 이용하여 Numeric 등록하기 <a href="#7.-numeric" id="7.-numeric"></a>

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FwIOTui0Tag1qTknJLrd2%2Fimage.png?alt=media\&token=830aa7b5-d0b2-43bd-bb6e-f0596c1d8868)

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FS7qi6YD2nLfrGPRYhuSO%2Fimage.png?alt=media\&token=6b792568-ac97-4dd2-9640-ff3bdda13720)

Parameter Type - Numeric 작성 예시

위 화면과 같이 Number(숫자) 형식으로 입력해야 하며 소수점, 정수 모두 입력 가능하다.

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FMiNnaV4U78iIXt24Oeet%2Fimage.png?alt=media\&token=241e1d6f-5eab-4d16-8cd3-1d98efd769ba)

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FRiGkFevwpCRDvwdfnOok%2Fimage.png?alt=media\&token=80e7c601-41ce-4111-889c-e3ec700883c0)

Parameter Type - Date 작성 예시

위 화면과 같이 Date(날짜) 형식으로 입력해야 한다.

#### 9. 배치 파일을 이용하여 Dictionary 등록하 <a href="#9.-dictionary" id="9.-dictionary"></a>

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FEWo1I49LR2LJSVZZdNLV%2Fimage.png?alt=media\&token=bdb5c1a4-fe3f-4933-9728-6d8f44c6c831)

Parameter Type - Dictionary 구조

![](https://2876966272-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FOwRsey49TEQIRDSGG3Db%2Fuploads%2FJyndiOTMYQQLCOB7ogR5%2Fimage.png?alt=media\&token=e1c9c35f-3ca2-4283-9a23-e6f54f4e3c30)

Parameter Type - Dictionary 작성 예시

위 화면과 같이 Value / Uncertainty 형식으로 입력해야 한다.
