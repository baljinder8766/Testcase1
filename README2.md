
        [Test]
        public void GetMultiplication_Input3_input2_Returns6()

        {
            //Arrange

            double number1 = 3;

            double number2 = 2;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetMultiplication();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);




        }



        [Test]
        public void GetMultiplication_Input33_input2_Returns66()

        {
            //Arrange

            double number1 = 33;

            double number2 = 2;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetMultiplication();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);

        }

        [Test]
        public void GetMultiplication_Input44_input2_Returns88()

        {
            //Arrange

            double number1 = 44;

            double number2 = 2;
            double expectedResult = number1 * number2;

            Calc testCalc = new Calc(number1, number2);
            //Act 

            double actualResult = testCalc.GetMultiplication();
            //Assert 
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetDivision_Input10_input2_Returns5()

        {
      
