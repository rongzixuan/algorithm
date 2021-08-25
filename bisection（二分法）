"""
二分法
"""

def bisection(nums, target):
	n = len(nums)
	left, right = 0, n-1
	
	while left < right:
		mid = left + (right-left)//2
		if nums[mid] == target:
			return mid
		elif nums[mid] > target:
			right = mid - 1
		elif nums[mid] < target:
			left = mid - 1
	return -1

nums = [3, 5, 6]
target = 5
res = bisection(nums, target)
print('res:', res)
