# nexmark

performance test of nexmark for flink and proton


## quick start

1. go to `python` folder
2. install dependencies `pip install -r requirements.txt`
3. run `python test.py --cases cases --targets target_platforms --size test_data_size`

for example `python test.py --cases q1,q2,q3 --targets flink,proton --size 10000000`

a csv report will be generated locally after test done.
