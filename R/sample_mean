#' Puts the various parts of speech together into a full phrase.
#'
#' @param vec A vector of numbers
#' @param n An integer
#'
#' @return A sample mean drawn from the values
#'
#' @export

add_value = function(vector, spot){
  return(vector[spot])
}

sample_mean = function(vec, n){
  random = round(runif(n, min = .5, max = .5+length(vec)))
  return(mean(sapply(random, function(y) add_value(vec, y))))
}
