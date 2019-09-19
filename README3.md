[Test]
        public void GetDivision_Input10_input2_Returns5()

        {
            //Arrange

            double number1 = 10;

            double number2 = 5;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetDivision();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);
        }


        [Test]
        public void GetDivision_Input20_input5_Returns4()

        {
            //Arrange

            double number1 = 20;

            double number2 = 5;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetDivision();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);


        }
        [Test]
        public void GetDivision_Input16_input2_Returns8()

        {
            //Arrange

            double number1 = 16;

            double number2 = 2;
            double expectedResult = number1 / number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetDivision();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input10_input2_Returns8()

        {
            //Arrange

            double number1 = 10;

            double number2 = 2;
            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetSubtraction();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);

        }



        [Test]
        public void GetSubtraction_Input30_input10_Returns20()

        {
            //Arrange

            double number1 = 30;

            double number2 = 10;
            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetSubtraction();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);



        }
         [Test]
        public void GetSubtraction_Input330_input110_Returns120()

        {
            //Arrange

            double number1 = 330;

            double number2 = 110;
            double expectedResult = number1 - number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetSubtraction();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);
        }

    
    }







}







