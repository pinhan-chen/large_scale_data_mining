#  Sentimental Regression Analysis

## Steps to regenerate the report

1. Download tweet data

```
wget --load-cookies /tmp/cookies.txt "https://docs.google.com/uc?export=download&confirm=$(wget --quiet --save-cookies /tmp/cookies.txt --keep-session-cookies --no-check-certificate 'https://docs.google.com/uc?export=download&id=1UEH11J3ViiegjpKwoUoCVO9BSKMfOXYi' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/\1\n/p')&id=1UEH11J3ViiegjpKwoUoCVO9BSKMfOXYi" -O data.zip && rm -rf /tmp/cookies.txt
```

2. Unzip data.zip

```
unzip data.zip
```

3. Make sure that putting your 'data' folder and 'tweet_data' in the same directory of your main.ipynb.

4. Modify the path in the first cell of notebook to yours local path. (if need)

5. Open main.ipynb and run it.

6. Then you should get the result similar to the one in my report successfully.



## Note
    
- For the question 1.1 ~ question 1.4, we use ydata_profiling.ProfileReport to answer. In which will generate a html file for the graphs you see in the notebook.

- I have attached the .html file and graphs in the folder for your reference. 


