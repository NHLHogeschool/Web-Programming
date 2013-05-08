!SLIDE center

# RSpec

!SLIDE

# Rspec

* TDD-framework voor Ruby;
* Integreert eenvoudig met Rails;
* Grondlegger van de nieuwe generatie.

!SLIDE

# Jasmine vs. RSpec

```javascript
describe("Calculator", function() {

  var calculator = new Calculator();

  it("should be able to add two numbers", function() {
    var calculation = calculator.add(2,3);
    expect(calculation).toEqual(5);
  })

})
```

```ruby
describe Calculator do

  let(:calculator) { Calculator.new }

  it "is able to add two numbers" do
    calculation = calculator.add 2, 3
    expect(calculation).to be_eql(5)
  end
end
```

!SLIDE center

# RSpec
## Demonstration
http://github.com/NHLHogeschool/RSpec

!SLIDE center

# RSpec Rails
## Demonstration
http://github.com/NHLHogeschool/blog
