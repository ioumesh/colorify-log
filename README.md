#colorify-log library
Usage Example:

import React from "react";

import { Log } from "colorifi-log";

const ConsoleLogger = () => {

  useEffect(() => {

    Log.info("Start");

    Log.success("Done");

    Log.danger("Error");

  }, []);

  return <div>Hi  colorifi-log</div>;

};



export default ConsoleLogger;