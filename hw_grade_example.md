**Homework 9**<br/>
<br/>
program1: 24/26<br/>
Should spawn the threads prior to reading the input in main. -2<br/>
Memory leak. Don't forget to free before exiting with error in the middle of your program. -2<br/>
Failed one test case with "segmentation fault". -2<br/>
I've attached the test file. Run this query: ./program1 failed_test.txt 763 1 1<br/>
<br/>
program2: 10/10<br/>
<br/>
total:    36/36<br/>


valgrind --tool=memcheck --leak-check=yes ./program1 ../../../instructors_2018/week11/program1_test_inputs/input1/test_data.txt 124 2 10 > result1

valgrind --tool=memcheck --leak-check=yes ./program1 ../../../instructors_2018/week11/program1_test_inputs/input2/test_data.txt 99 3 4

valgrind --tool=memcheck --leak-check=yes ./program1 ../../../instructors_2018/week11/program1_test_inputs/input3/test_data.txt 93 2 3 > result3

valgrind --tool=memcheck --leak-check=yes ./program1 ../../../instructors_2018/week11/program1_test_inputs/input4/test_data.txt 763 1 1

100 scores and 18 years, and 7 fortdays and 2 days

-----------------------------------
TA: Laura Zha <br/> Homework 8<br/>
-
bi, anqi: 31/36 <br/>
chang, ke: 0/36 <br/>
chen, xianyin: 36/36 <br/>
liu, tianyu: 0/36 <br/>
jiang, can: 0/36 <br/>
xi, zhenyuan: 32/36 <br/>
xu, tao: 0/36 <br/>
zhang, yiran: 0/36 <br/>
zheng, zhilong: 0/36 <br/>

-----------------------------------
// should sort by last name
xianyin_sp18 ** Xianyin Chen
brilliantjc_sp18 ** Can Jiang
taoxu_sp18 ** Tao Xu
zhengzhilong_sp18 ** Zhilong Zheng
changke1708_sp18 ** Ke Chang
sugarlade0401_sp18 ** Yiran Zhang
abi_sp18 ** Anqi Bi
stephenxi_sp18 ** Zhenyuan Xi
tianyuliu_sp18 ** Tianyu Liu



