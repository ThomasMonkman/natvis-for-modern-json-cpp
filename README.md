# natvis-for-modern-json-cpp
Visual studio natvis for JSON for Modern C++ ([nlohmann/json](https://github.com/nlohmann/json))

Should work on vs 2013+

### Example  
```c++
nlohmann::json json = {
  {"pi", 3.141},
  {"happy", true},
  {"name", "Niels"},
  {"nothing", nullptr},
  {"answer", {
    {"everything", 42}
  }},
  {"list", {1, 0, 2}},
  {"object", {
    {"currency", "USD"},
    {"value", 42.99}
  }}
};
```
Is visualised as    
![](https://github.com/ThomasMonkman/natvis-for-modern-json-cpp/blob/master/json_with_natvis.png)
