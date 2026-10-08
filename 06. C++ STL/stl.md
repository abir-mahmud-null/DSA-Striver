# C++ STL  

void functions > no return  
int functions > returns something

- STL
    - Algorithms
    - Containers
    - Functions
    - Iterators

## Pair
```cpp
pair<int,int> p = {1,3};
cout<<p.first;
cout<<p.second;

pair<int,pair<int,int>> P = {1,{1,3}};
cout<<p.second.first;  // shows 1
cout<<p.second.second; // shows 3

pair<int,int> arr[]={{1,2},{2,5},{5,1}};
cout<<arr[1].second; // shows 5
```

## Vector

```cpp
vector<int> v;    // {}
v.push_back(1);    // {1}
v.emplace_back(2);    // {1,2}

vector<pair<int,int>> vec;
v.push_back({1,2});
v.emplace_back(1,2);

vector<int> v(5,100); // {100,100,100,100,100}



