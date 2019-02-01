# Welcome to GraphiQL
#
# GraphiQL is an in-browser tool for writing, validating, and
# testing GraphQL queries.
#
# Type queries into this side of the screen, and you will see intelligent
# typeaheads aware of the current GraphQL type schema and live syntax and
# validation errors highlighted within the text.
#
# GraphQL queries typically start with a "{" character. Lines that starts
# with a # are ignored.
#
# An example GraphQL query might look like:
#
#     {
#       field(arg: "value") {
#         subField
#       }
#     }
#
# Keyboard shortcuts:
#
#  Prettify Query:  Shift-Ctrl-P (or press the prettify button above)
#
#       Run Query:  Ctrl-Enter (or press the play button above)
#
#   Auto Complete:  Ctrl-Space (or just start typing)
#

# for examples in https://medium.freecodecamp.org/an-introduction-to-graphql-how-it-works-and-how-to-use-it-91162ecd72d0
# -- follow below example test inputs
# {
#   movie(id: 1) {
#     name
#   }
# }

# {
#   movie(id: 3) {
#     name
#     id
#     year
#   }
# }

# {
#   director(id: 1) {
#     name
#     id,
#     age
#   }
# }

# {
#   director(id: 1) {
#     name
#     id,
#     age,
#     movies{
#       name,
#       year
#     }
#   }
# }