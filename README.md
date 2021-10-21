<details>
<summary>
:page_facing_up: Algorithms <sub>[Expand]</sub>
</summary>
<p>

> ```cs
> // supports System.Span<T> and any (non ref struct) int-indexed type
> IsPalindrome<...>(...);
> 
> // supports System.ReadOnlySpan<T>
> IsInterleavedRecursive<...>(...);
> IsInterleavedIterative<...>(...);
> 
> IsReorderOf<...>(...); // aka "anagrams"
> 
> // supports System.Span<T> and any (non ref struct) int-indexed type
> SortShuffle<T>(...);
> SortBubble<T>(...);
> SortSelection<T>(...);
> SortInsertion<T>(...);
> SortQuick<T>(...);
> SortMerge<T>(...);
> SortHeap<T>(...);
> SortOddEven<T>(...);
> SortCocktail<T>(...);
> SortComb<T>(...);
> SortGnome<T>(...);
> SortShell<T>(...);
> SortBogo<T>(...);
> SortSlow<T>(...);
> SortCycle<T>(...);
> SortPancake<T>(...);
> SortStooge<T>(...);
> SortTim<T>(...);
> SortCounting<T>(...); // uint-based (non-comparative sort)
> SortRadix<T>(...); // uint-based (non-comparative sort)
> SortPidgeonHole<T>(...); // int-based (non-comparative sort)
> 
> // supports System.ReadOnlySpan<T> and any (non ref struct) int-indexed type
> SearchBinary<T>(...);
> 
> // supports System.ReadOnlySpan<T> and any (non ref struct) int-indexed type
> int HammingDistanceIterative<...>(...);
> int LevenshteinDistanceRecursive<...>(...);
> int LevenshteinDistanceIterative<...>(...);
> 
> // Permutations of sequences
> // supports System.Span<T> and any (non ref struct) int-indexed type
> void PermuteRecursive<...>(...);
> void PermuteIterative<...>(...);
> 
> // Combinations of sequences
> void Combinations<...>(...);
> 
> // Path Finding (Graph Search)
> // overloads for A*, Dijkstra, and Breadth-First-Search algorithms
> SearchGraph<...>(...);
> 
> // Combines ranges without gaps between them
> IEnumerable<(T A, T B)> CombineRanges<T>(IEnumerable<(T A, T B)> ranges)
> ```
