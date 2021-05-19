  
#' Takes a vector and returns a vector of sample means drawn from the data
#'
#' @param vec A vector
#' @param n An integer
#' @param reps An integer
#'
#' @return A vector of sample means
#'
#' @export

many_sample_means = function(vec, n, reps){
  sample_vec = c(sapply(1:reps, function(y) sample_mean(vec, n)))
  return(sample_vec)
}
