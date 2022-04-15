# road_map_to_data_analyst


pandas, numpy => studying


pandas,numpy => 데이터 처리 및 조작에 사용. + datetime -> 시계열 데이터 사용 비중 높음.

pandas.series -> like enumerate (index, data ...)  +  dictionary frame.
                st = pd.Series([1,2,3,4],index = ['a','b','c','d'])
                st[['a','b']] => a 1 / b 2
                # list comprehension 사용 빈도 늘릴 것. 코드 가독성 높일 수 있을 듯.
                # list comprehesnion VS map 어떤 것이 속도면이나 메모리 사용면에서 차이를 알아보자.
                
                
pandas - 컬럼 단위로 접근하는데 용이. R의 dataframe을 차용하여 만든 것이 Pandas!

numpy - matrix관련 메서드와 matrix 산술계산 메서드를 포함.

td-idf => 문장에서 단어의 빈도수를 따지고 이를 가중치값을 곱하여 중요도를 환산하는 방식의 di 모델.
