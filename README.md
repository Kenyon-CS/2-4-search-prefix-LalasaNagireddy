[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/faDadley)
# 2.4 Search Prefix

def search_prefix(array, prefix)
  # Use select to filter items that start with the specified prefix
  result = array.select { |item| item.start_with?(prefix) }

  # Output the result
  puts result
end

# Input 1
input_array_1 = ["abcde", "abdf", "adeab", "abdgse", "bdefa", "bacdef"]
prefix_1 = "ab"
print "Input 1: "
search_prefix(input_array_1, prefix_1)

# Input 2
input_array_2 = ["abcde", "abdf", "adeab", "abdgse", "bdefa", "bacdef"]
prefix_2 = "b"
print "Input 2: "
search_prefix(input_array_2, prefix_2)
