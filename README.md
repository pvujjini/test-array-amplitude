# Array Amplitude - Test

_This should take you no more than 40 minutes._
_When you've finished create a pull request to submit your code for review._

A non-empty zero-indexed array A consisting of N integers is given. The _amplitude_ of this array is defined as the largest possible difference between two of its elements, i.e.:

    amplitude(A) = max( A[P] - A[Q] : 0 <= P, Q < N )
  
Write a method:

    public int solution(string s)

that, given a non-empty zero-indexed array A consisting of N integers, returns its amplitude.

For example, given array A such that:

    A[0] = 10
    A[1] = 2
    A[2] = 44
    A[3] = 15
    A[4] = 29
    A[5] = 20
    
the method should return 42.

Assume that:

* N is an integer within the range [1..1,000,000]
* each element of array A is an integer within the range [0..5,000,000]

Complexity:

* expected worst case time complexity is O(N)
* expected worst case space complexity is O(1), beyond input storage (not counting the storage required for input arguments)

Elements of input arrays can be modified
