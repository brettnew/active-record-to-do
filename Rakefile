require("./app")
require("sinatra/activerecord")
require("sinatra/activerecord/rake")
Dir.glob('lib/tasks/*.rake').each { |r| load r}

namespace(:db) do
  task(:load_config)
end
