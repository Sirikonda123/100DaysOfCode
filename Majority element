class Solution:
    def majorityElement(self, nums: List[int]) -> int:
        Candidate = None
        count = 0
        for num in nums:
            if count == 0:
                candidate = num
                count = 1
            elif num == candidate:
                count += 1
            else:
                count -= 1
        return candidate
solution = Solution()
nums = [2,2,1,1,1,2,2]
result = solution.majorityElement(nums)
print(result)
        
