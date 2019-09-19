using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

using NUnit.Framework;
using AwesomeCalculator;


namespace AwesomeCalculator
{



    class CalcTests
    {

        [Test]
        public void GetAddition_Input3point4and5point6_Returns9point0()

        {
            //Arrange

            double number1 = 3.4;

            double number2 = 5.6;
            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetAddition();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);





        }



        [Test]
        public void GetAddition_Input10andintput6_Returns16()

        {
            //Arrange

            double number1 = 10;

            double number2 = 6;
            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetAddition();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);
        }

        
 [Test]
        public void GetAddition_Input101andintput16_Returns117()

        {
            //Arrange

            double number1 = 101;

            double number2 = 16;
            double expectedResult = number1 + number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetAddition();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);
        }
    

        [Test]
        public void GetMultiplication_Input3_input2_Returns6()

        {
            //Arra
