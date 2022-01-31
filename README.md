# Caculate-Morgage
//Step 1   borrowed money = house price - down payment 
// step 2  owned money = interetst rate * borrowed money
// step 3  monthly payment = owned money / (years to pay *12) 
// JavaScript 

const morgageAmount = (interests, downPayment, housePrice) => {
    const moneyBorrow = housePrice - downPayment;
    const monthlyPayment = (moneyBorrow * interests) / 420;
    return `You are going to pay ${monthlyPayment}USD a month for 35 years fixed interetst rate.`;
}
console.log(morgageAmount(0.03, 50000, 600000));
