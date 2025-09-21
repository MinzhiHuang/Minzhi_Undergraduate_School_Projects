# ⚙️ Advanced Data Structures & Algorithms

**Course**: CMPT 225 - Data Structures and Programming  
**Skills**: C++ Programming, Algorithm Design, Data Structure Implementation  
**Tools**: C++, Object-Oriented Programming, Algorithm Analysis

## 🎯 Project Overview

This collection demonstrates mastery of fundamental computer science concepts through implementation of advanced data structures and algorithms. The projects showcase efficient, clean implementations with comprehensive testing and performance analysis.

## 🏗️ Data Structures Implemented

### Red-Black Trees

**Location**: `RedBlackTree/`  
**Skills**: Self-balancing trees, O(log n) operations, Tree rotations

- **Complete Implementation**: Full Red-Black tree with insert, delete, and search operations
- **Self-Balancing**: Automatic tree balancing to maintain O(log n) performance
- **Template Design**: Generic implementation supporting any comparable data type
- **Memory Management**: Proper resource management and cleanup
- **Testing Suite**: Comprehensive test cases covering edge cases and normal operations

**Key Features**:

- Insertion with automatic rebalancing
- Deletion with color adjustments and rotations
- Range queries and value retrieval
- Iterator support for tree traversal
- Memory-efficient node management

### Heap Data Structure

**Location**: `Heap/`  
**Skills**: Priority queues, Heap operations, Array-based implementation

- **Priority Queue**: Efficient implementation of max-heap priority queue
- **Dynamic Operations**: Insert, extract-max, and peek operations
- **Array-based**: Memory-efficient implementation using dynamic arrays
- **Template Support**: Generic implementation for different data types
- **Performance Optimization**: O(log n) insert/extract operations

**Key Features**:

- Efficient priority queue operations
- Dynamic resizing for memory optimization
- Template-based generic implementation
- Comprehensive error handling
- Performance validation through testing

### Sorting Algorithms

**Location**: `Sorting/`  
**Skills**: Algorithm analysis, Comparison-based sorting, Performance optimization

- **Multiple Algorithms**: Implementation of various sorting algorithms
- **Performance Analysis**: Comparative analysis of algorithm efficiency
- **Test Data**: Multiple test files for validation
- **Generic Implementation**: Template-based sorting for different data types
- **Benchmarking**: Performance comparison across different input sizes

**Key Features**:

- QuickSort, MergeSort, and other comparison-based algorithms
- Performance analysis and complexity evaluation
- Comprehensive testing with various input patterns
- Memory-efficient implementations
- Detailed documentation of algorithm choices

## 🛠️ Technical Implementation

### Code Quality

- **Clean Architecture**: Well-structured, modular code design
- **Error Handling**: Comprehensive exception handling and validation
- **Documentation**: Clear comments and documentation throughout
- **Memory Management**: Proper resource allocation and deallocation
- **Testing**: Extensive test suites for validation

### Performance Optimization

- **Algorithm Efficiency**: Optimal time and space complexity implementations
- **Memory Usage**: Efficient memory allocation and management
- **Cache Optimization**: Cache-friendly data structure layouts
- **Compilation**: Optimized compilation flags for performance

### Object-Oriented Design

- **Template Programming**: Generic implementations for type safety
- **Encapsulation**: Proper data hiding and interface design
- **Inheritance**: Appropriate use of inheritance where applicable
- **Polymorphism**: Interface-based design for flexibility

## 📊 Performance Analysis

### Red-Black Trees

- **Insertion**: O(log n) average and worst-case performance
- **Deletion**: O(log n) average and worst-case performance
- **Search**: O(log n) guaranteed performance
- **Space**: O(n) space complexity with efficient memory usage

### Heap Operations

- **Insert**: O(log n) time complexity
- **Extract-Max**: O(log n) time complexity
- **Peek**: O(1) time complexity
- **Build-Heap**: O(n) time complexity

### Sorting Algorithms

- **QuickSort**: O(n log n) average, O(n²) worst-case
- **MergeSort**: O(n log n) guaranteed performance
- **Space Complexity**: Analysis of auxiliary space requirements

## 📁 Project Structure

```
Data_Structures_RedBlackTree/
├── RedBlackTree/
│   ├── RedBlackTree.h      # Header file with class definition
│   ├── main.cpp            # Test driver and usage examples
│   └── Assignment/          # Assignment specifications
├── Heap/
│   ├── Heap.h              # Heap class header
│   ├── Heap.cpp            # Heap implementation
│   └── Readme              # Heap documentation
└── Sorting/
    ├── main.cpp            # Sorting algorithm implementations
    ├── cmpt225sort.h       # Sorting algorithm headers
    ├── a3test*.txt         # Test data files
    └── Readme              # Sorting documentation
```
