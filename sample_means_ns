
#' Puts the various parts of speech together into a full phrase.
#'
#' @param vec A vector of doubles or integers
#' @param reps A positive integer
#' @param ns A vector of positive integers
#'
#' @return A dataframe of sample means
#'
#' @export

sample_means_ns = function(vec, reps, ns){
  means = c()
  means = append(means, sapply(1:reps, function(y) sample_ns_intermediate(vec, ns)))
  data = data.frame(sample_means = means, n = ns)
  return(data)
}
sample_ns_intermediate = function(vec, ns){
  sample_vec = c(sapply(ns, function(y) sample_mean(vec, y)))
  return(sample_vec)
}
